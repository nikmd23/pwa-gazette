---
layout: page
title: Archive
permalink: /archive/
---

<div class="posts">
<ol>
  {% for post in site.posts %}
      <li>
        <strong><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></strong>
        <p><small>{{ post.excerpt }}</small></p>
      </li>
  {% endfor %}
  </ol>
</div>
