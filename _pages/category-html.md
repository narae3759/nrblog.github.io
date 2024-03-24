---
layout: archive
title: "HTML/CSS"
permalink: /html/
author_profiles: true
entries_layout: list
---

{% assign posts = site.categories.html %}
{% for post in posts %} 
  {% include archive-single.html type=page.entries_layout %} 
{% endfor %}
<a href="#page-title" class="back-to-top">{{ site.data.ui-text[site.locale].back_to_top | default: 'Back to Top' }} &uarr;</a>