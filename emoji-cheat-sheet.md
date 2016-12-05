---
title: Emoji Cheat Sheet
---

# {{ page.title }}  v0.11


{% for cat_hash in site.data.emojis %}

## {{ cat_hash[0] }}

{% for emoji in cat_hash[1] %}:{{emoji}}: `:{{emoji}}:`{% endfor %}

{% endfor %}
