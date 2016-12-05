---
title: More site.github Samples
---


{% for repo in site.github.public_repositories %}
* [{{ repo.name }}]({{ repo.html_url }})
{% endfor %}


site.github:
{{ site.github | jsonify }}
