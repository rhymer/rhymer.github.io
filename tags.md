---
layout: page
title: Tags
---

{% capture tags %}
  {% for tag in site.tags %}
    {{ tag[0] }}
  {% endfor %}
{% endcapture %}
{% assign sortedtags = tags | split:' ' | sort %}

{% for tag in sortedtags %}
  <h3 id="{{ tag }}">{{ tag }}</h3>
  <ul>
  {% for post in site.tags[tag] %}
    <li><p>{{ post.date | date_to_string }} &raquo; <a href="{{ post.url }}">{{ post.title }}</a></p></li>
  {% endfor %}
  </ul>
{% endfor %}
