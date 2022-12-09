---
layout: default
---

# Developer Log

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> <span style="float: right">{{post.date| date: "%m/%d/%y" }}</span>
    </li>
  {% endfor %}
</ul>