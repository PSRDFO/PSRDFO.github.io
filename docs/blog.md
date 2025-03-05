---
layout: page
title: Blog
permalink: /blog/
# Nav_include: yes
---

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}