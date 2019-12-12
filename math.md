---
layout: page
title: Math Corner
permalink: /math/
---

This page is for notes on math, statistics and programming concepts or projects I have encountered and want to remember.

{% for post in site.categories.math %}
 <li> &nbsp; <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}