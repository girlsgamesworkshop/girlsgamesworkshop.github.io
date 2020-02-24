{%- assign title_a = "Der Verein" -%}
{%- capture text_a -%}
Der Girls' Games Workshop wurde 2015 in Deutschand gegründet und ist eine gemeinnützige Organisation.
<br>Seit anfang 2020 sind wir ein eingetragener Verein.
{%- endcapture -%}


{%- assign title_b = "Unsere Workshops" -%}
{%- capture text_b -%}
Wir veranstalten 1-Tages-Workshops für junge Mädchen, denen wir die Grundlagen des Game Design sowie der Programmierung beibringen. Der Fokus dieser Workshops liegt vor allem auf praktischen Übungen in denen die Mädchen ihr auch ein eigenes Spiel entwickeln.
<br>In der Regel streben wir ein Verhältnis von einem Lehrer auf drei Schülerinnen an um sicherzustellen, dass wir die bestmögliche Betreuung anbieten können und die Mädchen möglichst viel lernen.
{%- endcapture -%}


{%- assign title_c = "Das Team" -%}
{%- capture text_c -%}
Geleitet wird der Workshop von ehrenamtlichen Helfern, die alle in unterschiedlichen deutschen Spielefirmen arbeiten und richtet sich an Mädchen im Alter von 12 - 15 Jahren.
{%- endcapture -%}


{%- include _txt_img_section.html image="/assets/img/landing_1.jpg" right=true headline=title_a text=text_a -%}
{%- include _txt_img_section.html image="/assets/img/landing_2.jpg" right=false headline=title_b text=text_b -%}
{%- include _txt_img_section.html image="/assets/img/landing_3.jpg" right=true headline=title_c text=text_c -%}