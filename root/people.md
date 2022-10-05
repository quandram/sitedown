---
layout: default
title: People
---
# People

{% for person in site.people %}
  - ## <a href="{{ person.url }}">{{ person.name }}</a>
    - {{ person.content | markdownify }}
{% endfor %}