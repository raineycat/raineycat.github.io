---
title: Welcome!
---

### Recent posts (newest first)

{% for item in site.posts %}
  - [{{ item.title }}]({{ item.url }}) by *{{ item.author }}*
{% endfor %}

