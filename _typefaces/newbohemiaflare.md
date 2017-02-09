---
layout: typeface_individual
title: newbohemianflare
typeface: New Bohemian Flare
designer: Damon Styer
permalink: /newbohemianflare/

sections:
  typefaceBlurb: 
  bio: Damon is the proprietor of New Bohemia Signs, a sign painting shop in San Francisco.

website: https://www.newbohemiasigns.com/
instagram: nbsigns


---

<div class="typeface__images">
{% for file in site.static_files %}
  {% if file.path contains 'img/newbohemianflare/' %}
    <img src="{{ file.path }}" />
  {% endif %}
{% endfor %}
</div>
