---
layout: default
title: Главная
---
# Добро пожаловать в Array Comics

## Выпуски:
{% for page in site.pages %}
{% if page.url contains '/comics/' %}
- [{{ page.title }}]({{ page.url }})
{% endif %}
{% endfor %}
