---
title: Resources
layout: default
permalink: /resources/
---
<h1>Resources</h1>

{% for resource in site.resources %}
  <h3>{{ resource.title }}</h3>
  <p>{{ resource.content }}</p>
  <a href="{{ resources.source }}" target="_blank">Source</a>
{% endfor %}
