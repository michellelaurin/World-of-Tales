---
title: Australia
layout: default
permalink: /australia/
---
<h1>Australia's Folk and Fairy Tales</h1>

{% for tale in site.tales %}
  <h3>{{ tale.title }}</h3>
  <p>{{ tale.content }}</p>
  <a href="{{ tale.source }}" target="_blank">Source</a>
{% endfor %}
