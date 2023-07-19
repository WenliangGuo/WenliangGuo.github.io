---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---
You can find my full publication list on [Scholar profile](https://scholar.google.com/citations?hl=en&user=nGrpGjkAAAAJ)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
