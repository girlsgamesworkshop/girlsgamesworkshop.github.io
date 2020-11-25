{%- assign title_a = "Der Verein" -%}
{%- capture text_a -%}
Der Girls' Games Workshop wurde 2015 in Deutschand gegründet und ist eine gemeinnützige Organisation.
<br>Seit Ende 2019 sind wir ein eingetragener Verein.
{%- endcapture -%}


{%- assign title_b = "Unsere Workshops" -%}
{%- capture text_b -%}
Wir veranstalten eintägige Workshops für Mädchen, denen wir die Grundlagen des Game Designs sowie der Programmierung beibringen. Die Theorie kann direkt in praktischen Übungen ausprobiert werden, bevor es dann an die Entwicklung des ersten eigenen Spiels geht.
<br>Wir versuchen pro drei Teilnehmerinnen jeweils eine Tutorin oder einen Tutor an Bord zu haben, sodass wir die Mädchen bestmöglich bei der Umsetzung ihrer Projekte unterstützen können.
{%- endcapture -%}


{%- assign title_c = "Das Team" -%}
{%- capture text_c -%}
Geleitet wird der Workshop von ehrenamtlichen Helferinnen und Helfern, die in unterschiedlichen deutschen IT-Firmen arbeiten und ihre Begeisterung für die Spieleentwicklung weitergeben möchten.
{%- endcapture -%}


{%- include _txt_img_section.html image="/assets/img/landing_1.jpg" right=true headline=title_a text=text_a -%}
{%- include _txt_img_section.html image="/assets/img/landing_2.jpg" right=false headline=title_b text=text_b -%}
{%- include _txt_img_section.html image="/assets/img/landing_3.jpg" right=true headline=title_c text=text_c -%}