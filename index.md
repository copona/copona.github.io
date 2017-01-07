---
layout: default
title: {{ site.name }}
---

## Welcome to Copona


Ecommerce engine. Based on Opencart. Improved.


Generated with [Jekyll](https://jekyllrb.com/) from `_config.yml`


<div id="home">
  <h1>Blog Posts</h1>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</div>

