---
layout: page
permalink: /talks/
title: Talks
#description: List of recent talks.
nav: true
nav_order: 2
#display_categories: [work, fun]
horizontal: false
---

{% include workinprogress.html %}

{% for item in site.news %}
  {% if item.name == "talk_rutgers" %}
    {% assign url = item.url | relative_url %}
  {% endif %}
{% endfor %}

You can also watch the video of my [talk at Rutgers Business School]({{ url }}), on June 29th.
