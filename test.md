---
layout: page
title: test
permalink: /test.html
---
{% include pagi %}

{% for post in paginator.posts %}
{{post.url}}
  {% include view_grid %}
{% endfor %}