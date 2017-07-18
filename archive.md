---
layout: page
title: Archive
permalink: /archive/
---

<div class="posts">
<ol>
  {% for post in site.posts %}
      <li>
        <strong><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></strong> - {{ post.date | date: "%-d %B %Y"}}
        <p>{{ post.excerpt }}</p>
      </li>
  {% endfor %}
  </ol>
</div>
