---
layout: page
title: Home
id: home
permalink: /
---

Hey, I'm Marco 👋

You found my digital garden, feel free to have a look around and explore. The main purpose of this place is to create the right conditions for ideas to develop, grow, and form connections across disciplines.

At the end of each note, you'll find a series of backlinks, pointing to all the notes connected to the one you are reading.

These notes are not meant to be static. They exist with the very purpose to evolve, change, and form new connections over time. They are often referred to as [[Evergreen notes]].

Ultimately, the end goal of creative research is to be able to connect the dots and get a sense of the bigger picture. This is my attempt at doing so.

I try to focus on [[Now|a few things at a time]] at most, aiming for a healthy balance between creating and consuming ideas.

I also have a bunch of [[Loose ends|loose ends]], things I've been exploring but have not found a proper place for, yet.

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes | limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
