---
layout: single
title: "My Digital Garden"
permalink: /garden/
header:
  overlay_color: "#1b5e20" # A nice green header color
  overlay_image: /assets/images/garden.jpg # (Optional) Use a nice background image
---

Welcome to my **Digital Garden**. This is a collection of unfinished, evolving thoughts and evergreen knowledge, constantly being refined. It is less a blog and more a public workspace.

---

## Evergreen Notes

{% assign garden_notes = site.garden | sort: "title" %}

{% for item in garden_notes %}
- [{{ item.title }}]({{ item.url | relative_url }}) 
    - <small>Updated: {{ item.date | date: "%B %d, %Y" }}</small>
{% endfor %}