---
title: Tales
layout: default
permalink: /tales/
---
<h1>Annotated Bibliographies</h1>

{% for tale in site.tales %}
  <h3>{{ tale.title }}</h3>
  <p>{{ tale.content }}</p>
  <a href="{{ tale.source }}" target="_blank">Source</a>
{% endfor %}
