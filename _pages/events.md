---
title: "Events"
permalink: /events/
layout: single
classes: wide
sidebar: false
toc: false
---
<div class="events-grid">
{% assign events = site.posts | where_exp: "p", "p.categories contains 'events'" | sort: "date" | reverse %}
{% for post in events %}
  <a class="event-card" href="{{ post.url | relative_url }}">
    {% if post.header.teaser %}
      <img
        class="event-card__img"
        src="{{ post.header.teaser | relative_url }}"
        alt="{{ post.title }}">
    {% endif %}
    <div class="event-card__body">
      <div class="event-card__title">{{ post.title }}</div>
      <div class="event-card__meta">{{ post.date | date: "%-d %B %Y" }}</div>
      {% if post.excerpt %}
        <div class="event-card__excerpt">
          {{ post.excerpt | strip_html | truncate: 140 }}
        </div>
      {% endif %}
    </div>
  </a>
{% endfor %}
</div>
