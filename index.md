---
layout: home
title: Select your language
---

## Выберите ваш язык

{% for lang in site.data.lang %}
- [{{lang[1].label}} ({{lang[0]}})]({{site.baseurl}}/{{lang[0]}}/)
{% endfor %}
