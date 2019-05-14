---
layout: novichku-category
title: Программы Блокчейна и Криптовалют - самые Важные (сегодня)
permalink: /novichku/
---



<div class="posts">
{% for post in site.categories.Novichku %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Читать дальше</a>
    </article>
  {% endfor %}
</div>

