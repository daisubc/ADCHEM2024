---
layout: page
title: Announcements
subtitle: Updates and Important Notices
show-avatar: False
---

{% assign announcements = site.data.announcements | sort: 'date' | reverse %}

<ul class="list-group">
  {% for a in announcements %}
    <li class="list-group-item d-flex">
      <p>
      <small>{{ a.date | date_to_long_string: "ordinal", "US" }}</small>
      <br>
      {% if a.link %}
        <b><a href="{{a.link}}">{{ a.title }}</a></b>
      {% else %}
        <b>{{ a.title }}</b>
      {% endif %}
      <br>
      {{ a.text }}
      </p>
    </li>
  {% endfor %}
</ul>