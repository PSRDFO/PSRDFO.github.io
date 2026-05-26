---
layout: page
title: Select Projects
permalink: /projects/
---
This will hold a description of some ongoing projects that PSR are engaged with (hopefully each with a description and link to a repo) and that we think are worth highlighting.

Examples:
- salmonMSE?
- samSim and samEst?
- stockseasonr? 
- recent PSSI project and links to them? 


{% for post in site.projects %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
