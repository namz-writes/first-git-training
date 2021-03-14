---
layout: template_demo
author: Namrata
---


# Home Page of My First Git Project

Hi, My name is {{ page.author }}. This is my first attempt creating a project on Git.

This page is part of {{ site.what }} in the {{ site.when }} batch.

Using Liquid command to publish csv data

{% for item in site.data.employment %}
{{ item.company }}, {{ item.years }} 
{% endfor %}