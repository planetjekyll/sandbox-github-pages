---
title: Emoji Cheat Sheet
---

# {{ page.title }}


{% for cat_hash in site.data.emojis %}

## {{ cat_hash[0] }}

{% for emoji in cat_hash %}
`:{{emoji}}:` :{{emoji}}: 
{% endfor %}

{% endfor %}

