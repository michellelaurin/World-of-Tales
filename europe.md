---
title: Europe
layout: default
permalink: /europe/
---
<h1>Europe's Folk and Fairy Tales</h1>

{% for tale in site.europe_tales %}
  <h3>{{ europe_tale.title }}</h3>
  <p>{{ europe_tale.content }}</p>
  <a href="{{ europe_tale.source }}" target="_blank">Source</a>
{% endfor %}
