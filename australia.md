---
title: Australia
layout: default
permalink: /australia/
---
<h1>Australia's Folk and Fairy Tales</h1>

<h2>History</h2>

<h2>Popular Stories</h2>

{% for australia_tale in site.australia_tales %}
  <h3>{{ australia_tale.title }}</h3>
  <p>{{ australia_tale.content }}</p>
  <a href="{{ australia_tale.source }}" target="_blank">Source</a>
{% endfor %}
