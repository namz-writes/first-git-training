---
layout: template_other
title: Source of Materials
---
# {{page.title}}

The following are some sources that you can look out for collecting materials for your upcycling projects:

{% for item in site.data.source %}
 - {{ item.material }}: {{ item.source }}

{% endfor %}

## See Also

 - [Difference between Upcycling and Recycling](./recycle-upcycle)
 - [Inspiring Upcycle Ideas](./inspirations)
 - [Benefits of Upcycling](./benefits)
 



