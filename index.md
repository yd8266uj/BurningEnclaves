---
layout: default
title: Home page
---
{% for post in site.posts %}
  - ## {{ post.title }} ## ### {{ post.summary }} ### [Detail]({{ site.baseurl }}{{ post.url }})
{% endfor %}
