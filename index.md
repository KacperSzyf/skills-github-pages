---
title: Welcome to my blog
---

# Landing Page

this is a landing page for test.

## post list
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>