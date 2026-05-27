---
layout: page
title: Opportunities
permalink: /opportunities/
---
This will hold a description of some ongoing opportunities alongside PSR DFO.

{% for post in site.opportunities %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}