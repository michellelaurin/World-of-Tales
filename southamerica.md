---
title: South America
layout: default
permalink: /southamerica/
---
<h1>South America's Folk and Fairy Tales</h1>

<h2>History</h2>

<h2>Popular Stories</h2>

{% for southamerica_tale in site.southamerica_tales %}
  <h3>{{ southamerica_tale.title }}</h3>
  <p>{{ southamerica_tale.content }}</p>
  <a href="{{ southamerica_tale.source }}" target="_blank">Source</a>
{% endfor %}
