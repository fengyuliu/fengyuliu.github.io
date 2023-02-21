---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my publications on <u><a href="https://scholar.google.com/citations?user=SsX0jh0AAAAJ">my Google Scholar profile</a>.</u>

## Articles
{% include base_path %}

{% for post in site.articles reversed %}
  {% include archive-single.html %}
{% endfor %}

## Proceedings
{% include base_path %}

{% for post in site.proceedings reversed %}
  {% include archive-single.html %}
{% endfor %}

