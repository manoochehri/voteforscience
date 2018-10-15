---
layout: page
title: Legislators by State
permalink: "/legislators/"
exclude: true
---

<ul>
  {% for legislator in site.legislators %}
      <!-- li -->
        <a href="{{ legislator.url }}"><h3>{{ legislator.title }}</h3></a>
      <!-- /li -->
  {% endfor %}
</ul>
