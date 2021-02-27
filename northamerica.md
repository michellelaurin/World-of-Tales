---
title: North America
layout: default
permalink: /northamerica/
---
<h1>North America's Folk and Fairy Tales</h1>

<h2>History</h2>

<h2>Popular Stories</h2>

{% for northamerica_tale in site.northamerica_tales %}
  <h3>{{ northamerica_tale.title }}</h3>
  <p>{{ northamerica_tale.content }}</p>
  <a href="{{ northamerica_tale.source }}" target="_blank">Source</a>
{% endfor %}
