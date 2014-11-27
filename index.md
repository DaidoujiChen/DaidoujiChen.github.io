---
layout: page
title: Daidouji 記事本
tagline: 記有的沒有的事情
---
{% include JB/setup %}

## 最新的發文

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


