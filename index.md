---
layout: default
title: Home page
---
{% for post in site.posts %}
  ## {{ post.title }}
  [{{ post.summary }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}
