---
layout: typeface_individual
title: florence
typeface: Florence
designer: Kim Rhee
permalink: /florence/

sections:
  typefaceBlurb: 
  bio: Kim is a freelance designer living in San Francisco.




---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/florence/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
