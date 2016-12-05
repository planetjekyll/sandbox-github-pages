---
title: Debug Settings
---

## Site Settings

- site.url: >{{ site.url }}<
- site.baseurl: >{{ site.baseurl }}<

## Markdown Settings

{{ site.markdown | jsonify }}

## Highlighter Settings

{{ site.highlighter | jsonify }}

## Kramdown Settings

{{ site.kramdown | jsonify }}

## GitHub Settings

{{ site.github | jsonify }}

## GitHub Pages Versions

{{ site.github.versions | jsonify }}
