---
layout: default
title: Home page
---
<ul>
{% for post in site.posts %}
  <li>
    ## {{ post.title }}
    ### {{ post.summary }}
    [Detail]({{ site.baseurl }}{{ post.url }} "{{ post.summary }}")
  </li>
{% endfor %}
</ul>
