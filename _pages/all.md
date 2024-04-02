---
layout: page
title: All
id: all
permalink: /all
---

<strong>All notes</strong>

<ul>
  {% assign all_notes = site.notes | sort: "title" %}
  {% for note in all_notes %}
    <li>
      <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

