---
layout: page
title: news
permalink: /news/
---


{% for post in site.categories.News %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

Some information about you!

### More Information

A place to include any other types of information that you'd like to include about yourself.

### Contact me

[email@domain.com](mailto:email@domain.com)