---
layout: default
title: blog posts
---

###{{ page.title }}###

<ul>
{% for post in site.posts %}
  <li>
  <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}

</ul>
[Atom Feed](http://randomness.org.uk/atom.xml)