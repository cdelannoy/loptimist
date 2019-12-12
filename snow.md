---
layout: page
title: Snowpack
permalink: /snowpack/
---

This page is for notes on the implementation of the Northeastern Snowpack project.

![snowAtZealand](../assets/images/DSC01147.JPG)

{% for post in site.categories.snow %}
 <li> &nbsp; <a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}