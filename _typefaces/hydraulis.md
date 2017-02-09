---
layout: typeface_individual
title: hydraulis
typeface: Hydraulis
designer: Lauren Hostetter
permalink: /hydraulis/

sections:
  typefaceBlurb:
  bio: Lauren is an illustrator and designer living in Sacramento.

website:
instagram:
twitter:
linkedin:
facebook:


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/hydraulis/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
