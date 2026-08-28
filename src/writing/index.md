---
layout: base.njk
title: Writing
permalink: /writing/
---
{% if collections.posts and collections.posts.length %}
<ul class="posts">
{% for post in collections.posts | reverse %}
  <li>
    <a href="{{ post.url }}">{{ post.data.title }}</a>
  </li>
{% endfor %}
</ul>
{% else %}
Posts go here.
{% endif %}
