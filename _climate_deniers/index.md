---
layout: page
title: "Climate Denier List by State"
---

<ul>
  {% for climate_deniers in site.climate_deniers %}
    <li>
      <a href="{{ climate_deniers.url }}">{{ climate_deniers.title }}</a>
    </li>
  {% endfor %}
</ul>
