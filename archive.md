---
layout: page
title: Archive
permalink: /archive/
---

<div class="posts">
<ol>
  {% for post in site.posts %}
      <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </ol>
</div>
