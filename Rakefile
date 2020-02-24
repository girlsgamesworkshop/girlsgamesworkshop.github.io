$ENV_FILE = __dir__ + '/.git/rake_env.rb'

task default: [:help]

task :help do
  puts 'Run \'rake -T\' to get an overview of all available tasks.'
end

desc 'Installs all dependencies'
task :install do
  if !File.file?($ENV_FILE)
    sh "echo \"\# \\$SSH_KEY = ''\" >> #{$ENV_FILE}"
    sh "echo \"\# \\$DEST_HOST = ''\" >> #{$ENV_FILE}"
  end
  sh 'gem install bundler'
  sh 'bundle install'
end

desc 'Does a clean site build'
task :build do
  sh 'bundle exec jekyll clean'
  sh 'bundle exec jekyll build'
end

desc 'Does a build and then locally serves the site with autoreload'
task :watch do
  sh 'bundle exec jekyll s --livereload'
end

desc 'Deploys to staging server'
task deploy: [:check_env, :build] do
  sh "ssh-add #{$SSH_KEY}"
  sh "scp -r _site/* #{$DEST_HOST}"
end

task :check_env do
  require($ENV_FILE)
  if $SSH_KEY.nil? || $DEST_HOST.nil?
    raise "\$SSH_KEY and \$DEST_HOST needs to be defined in #{$ENV_FILE}"  
  end
end