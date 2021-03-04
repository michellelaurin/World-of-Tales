---
title: The World Of Folk And Fairy Tales
layout: default
permalink: /bibliographies/
---
<h1>Annotated Bibliographies</h1>
{% for bibliographie in site.bibliographies %}
  <h3>{{ bibliographie.title }}</h3>
  <p>{{ bibliographie.content }}</p>
  <a href="{{ bibliographie.source }}" target="_blank">Source</a>
{% endfor %}
