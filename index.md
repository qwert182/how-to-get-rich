---
layout: home
title: Select your language
---

{% for lang in site.data.languages %}
{% assign language = lang[1] %}
- [{{language.label}} ({{lang[0]}})]({{site.baseurl}}/{{lang[0]}}/)
{% endfor %}
