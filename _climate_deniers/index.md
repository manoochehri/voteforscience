---
layout: page
title: Climate Deniers by State
permalink: "/climate_deniers/"
exclude: true
---

<ul>
  {% for climate_denier in site.climate_deniers %}
    {% unless climate_denier.exclude %}
      <!-- li -->
        <a href="{{ climate_denier.url }}"><h3>{{ climate_denier.link_text }}</h3></a>
      <!-- /li -->
      {% endunless %}
  {% endfor %}
</ul>
