---
layout: default
title: Home page
---
{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  [{{ post.summary }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
