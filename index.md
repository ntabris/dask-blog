---
layout: page
title: Dask Working Notes
---

{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    {% if post.draft != true %}
    <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>: <i>{{ post.date | date_to_string }}</i> </li>
    {% endif %}
  {% endfor %}
</ul>
