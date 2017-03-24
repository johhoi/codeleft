---
layout: default
title: Codeleft
---

## Codeleft 
This site is about politics and coding, and especially where coding is combined with the political left. It is a starting point for, on the one hand help people already decided to find out how they can help out, and on the other hand to invigorate people to actually get involved.

The idea of this site is to collect and link code projects that either are directly political or that could be a tool for people being directly political.

It is a left leaning political think tank for code  
-- A _code-tank!_  

&nbsp;
&nbsp;

#### The latest news posts
{% for post in site.posts %}

<div>
  {{ post.date | date: "%b %-d, %Y" }}
    »
  <span class='post-title'>
    <a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a>
  </span>
</div>

{% endfor %}
