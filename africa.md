---
title: Africa
layout: default
permalink: /africa/
---
<h1>Africa's Folk and Fairy Tales</h1>

<h2>History</h2>

<h2>Popular Stories</h2>

{% for africa_tale in site.africa_tales %}
  <h3>{{ africa_tale.title }}</h3>
  <p>{{ africa_tale.content }}</p>
  <a href="{{ africa_tale.source }}" target="_blank">Source</a>
{% endfor %}
