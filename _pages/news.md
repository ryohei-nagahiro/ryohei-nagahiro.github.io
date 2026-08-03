---
layout: archive
title: "News Archive"
permalink: /news/
author_profile: true
---

{% for item in site.data.news.en %}
- **{{ item.date }}**: {{ item.text }}{% if item.link %} [<a href="{{ item.link }}" target="_blank">Link</a>]{% endif %}
{% endfor %}