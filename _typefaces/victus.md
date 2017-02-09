---
layout: typeface_individual
title: victus
typeface: Victus
designer: Gen Ramirez
permalink: /victus/

sections:
  typefaceBlurb:
  bio: Gen is a type designer/letter/calligrapher based in Guadalajara, Mexico.

website:
instagram: genramirez
twitter:
linkedin:
facebook:


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/victus/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
