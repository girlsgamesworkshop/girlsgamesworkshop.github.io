{%- assign title_a = "Our Organisation" -%}
{%- capture text_a -%}
Girls' Games Workshop was founded in Germany in 2015, and is a non profit organization run by volunteers.
<br>Since beginning of 2020 we are an offical<br> "eingetragener Verein" (e.V).
{%- endcapture -%}


{%- assign title_b = "Our Workshops" -%}
{%- capture text_b -%}
We currently run one-day workshops aimed to teach young girls about game design and game programming through a series of short lectures and lots of hands on learning.<br>Our workshops aim for a ratio of 3:1 of teacher's assistants to girls attending to ensure the attendees get the most out of it.
{%- endcapture -%}


{%- assign title_c = "The Team" -%}
{%- capture text_c -%}
This workshop is led by volunteers who work in the gaming industry throughout Germany. It targets girls between the ages 12 -15.
{%- endcapture -%}


{%- include _txt_img_section.html image="/assets/img/landing_1.jpg" right=true headline=title_a text=text_a -%}
{%- include _txt_img_section.html image="/assets/img/landing_2.jpg" right=false headline=title_b text=text_b -%}
{%- include _txt_img_section.html image="/assets/img/landing_3.jpg" right=true headline=title_c text=text_c -%}