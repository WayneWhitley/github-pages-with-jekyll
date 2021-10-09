---
title: "Welcome -- now what in the world are we here to discuss??"
---

I'm glad you are here. I plan to talk about ...

**bold** and this is *italic*

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/github-pages-with-jekyll{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
