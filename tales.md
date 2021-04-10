---
title: The World Of Folk And Fairy Tales
layout: default
permalink: /tales/
---
<h1>Tales From Around The World</h1>

{% for tale in site.tales %}
  <div class="teaser-content">
  <h3><a href="{{ tale.url }}" alt="go to the detail page">{{ tale.title }}</a></h3>
  <p>{{ tale.content | truncatewords: 50, "..." }}</p>
  <a href="{{ tale.source }}" target="_blank">Source</a>
{% endfor %}
