{%- assign title_a = "Our Organisation" -%}
{%- capture text_a -%}
Girls' Games Workshop was founded in Germany in 2016, and is a non profit organization run by volunteers.
<br>Since the end of 2019 we are an offical<br> "eingetragener Verein" (e.V).
{%- endcapture -%}


{%- assign title_b = "Our Workshops" -%}
{%- capture text_b -%}
We currently run one-day workshops to teach girls about game design and programming. We provide a mix of presentations and coding tasks to cover the basics before we let the girls start working on their very own first game.<br> One Tutor takes care of three participants to ensure all their questions are covered and they get the support they need.
{%- endcapture -%}


{%- assign title_c = "The Team" -%}
{%- capture text_c -%}
This workshop is led by volunteers working in the IT industry throughout Germany. We want to inspire girls to become interested in game development.
{%- endcapture -%}


{%- include _txt_img_section.html image="/assets/img/landing_1.jpg" right=true headline=title_a text=text_a -%}
{%- include _txt_img_section.html image="/assets/img/landing_2.jpg" right=false headline=title_b text=text_b -%}
{%- include _txt_img_section.html image="/assets/img/landing_3.jpg" right=true headline=title_c text=text_c -%}