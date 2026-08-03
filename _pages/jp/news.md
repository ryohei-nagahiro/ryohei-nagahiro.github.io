---
layout: archive
title: "お知らせ一覧"
permalink: /jp/news/
author_profile: true
lang: jp
author: author_jp
---

{% for item in site.data.news.jp %}
- **{{ item.date }}**：{{ item.text }}{% if item.link %} [<a href="{{ item.link }}" target="_blank">リンク</a>]{% endif %}
{% endfor %}