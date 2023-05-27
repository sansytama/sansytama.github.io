---
layout: page
title: Drafts
permalink: /drafts/
---

{% for post in site.categories.drafts %}
  {{ post.output }}
{% endfor %}
