---
layout: post
title: "External Resources"
category: guide
tags: Green
---

## Other guides

{% for entry in site.data.resources | sort %}
  <ul>
    {% if page.tags contains entry.spirit %}
      <li><a href="{{ entry.link }}">{{ entry.author }}'s guide on {{ entry.site }}</a></li>
    {% endif %}
  </ul>
{% endfor %}
