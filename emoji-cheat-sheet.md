---
title: Emoji Cheat Sheet
---


{% for cat_hash in site.data.emojis %}

{{ cat_hash[0] }}

{{ cat_hash[1] | jsonifiy }}

{% endfor %}
