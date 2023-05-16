---
layout: home
limit: 10
show_excerpts: true
entries_layout: list
---
{% for lang in site.languages %}
    {% if lang == site.default_lang %}
{{ lang }} (Default)
    {% else %}
{{ lang }}
    {% endif %}
{% endfor %}