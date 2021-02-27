---
title: Asia
layout: default
permalink: /asia/
---
<h1>Asia's Folk and Fairy Tales</h1>

<h2>History</h2>

<h2>Popular Stories</h2>

{% for asia_tale in site.asia_tales %}
  <h3>{{ asia_tale.title }}</h3>
  <p>{{ asia_tale.content }}</p>
  <a href="{{ asia_tale.source }}" target="_blank">Source</a>
{% endfor %}
