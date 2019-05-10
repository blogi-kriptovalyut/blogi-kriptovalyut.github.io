---
layout: news
title: Криптовалюта новости и  прогнозы. [Самое важное] - 2019
permalink: /news/
---

<h1>Новочти</h1>
{% for post in site.categories.news %}
    <time>{{ post.date | date: "%b %-d, %Y" }}</time>
    <h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
{% endfor %}



Some information about you!

### More Information

A place to include any other types of information that you'd like to include about yourself.

### Contact me

[email@domain.com](mailto:email@domain.com)