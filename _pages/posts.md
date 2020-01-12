---
title: Posts
permalink: /posts/
header:
  overlay_image: /assets/images/posts.jpg
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
