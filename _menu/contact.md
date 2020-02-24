---
layout: page
title: menu.title_contact
description: menu.desc_contact
---

{%- assign mail = site.email | replace: "@", " [at] " -%}
{%- assign mail = mail | replace: ".", " [dot] " -%}

{%- translate_file _menu/contact.md -%}