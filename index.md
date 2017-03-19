---
layout: default
title: Codeleft
---

## CodeLeft 
-- a left leaning political think tank for code - A _code-tank_





#### The latest posts from the blog
{% for post in site.posts %}

<div>
  {{ post.date | date: "%b %-d, %Y" }}
    »
  <span class='post-title'>
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </span>
</div>

{% endfor %}
