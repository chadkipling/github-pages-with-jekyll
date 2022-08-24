---
title: "Welcome to my blog Kip"
---

I'm glad you are here. I plan to talk about ... mah tags...

{% for tag in site.tags %}
  Name: {{ tag | first }},
  count: {{ tag | last | size}}
{% endfor %}
