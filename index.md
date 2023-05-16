---
layout: home
limit: 10
show_excerpts: true
entries_layout: list
---
{% for lang in site.languages %}
{{ lang }}
{% endfor %}