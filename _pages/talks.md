---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: false
---

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single-talk.html %}
{% endfor %}
