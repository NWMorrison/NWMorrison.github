---
layout: page
title: Text Mining
permalink: /blog/categories/Text-Mining/
---

<h5> Posts by Category : {{ page.title }} </h5>

<div class="card">
{% for post in site.categories.Text-Mining %}
    <div class="category-posts"><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></div>
{% endfor %}
</div>