---
title: "Events"
permalink: /events/
layout: single
classes: wide
sidebar: false
toc: false
---
<div class="events-list">
{% assign events = site.posts | where_exp: "p", "p.categories contains 'events'" | sort: "date" | reverse %}
{% for post in events %}
  <article class="event-row">
    <div class="event-row__text">
      <h2 class="event-row__title">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h2>
      <div class="event-row__meta">{{ post.date | date: "%-d %B %Y" }}</div>

      {% if post.excerpt %}
        <p class="event-row__excerpt">{{ post.excerpt | strip_html }}</p>
      {% endif %}

      <p class="event-row__link">
        <a href="{{ post.url | relative_url }}">Read more →</a>
      </p>
    </div>

    <div class="event-row__media">
      {% if post.header.teaser %}
        <a href="{{ post.url | relative_url }}">
          <img class="event-row__img" src="{{ post.header.teaser | relative_url }}" alt="{{ post.title }}">
        </a>
      {% endif %}
    </div>
  </article>
{% endfor %}
</div>
