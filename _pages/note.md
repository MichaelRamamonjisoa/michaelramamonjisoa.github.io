---
layout: archive
title: "Note"
permalink: /note/
author_profile: false
redirect_from:
  - /note
---

{% include base_path %}


<!-- include all .md files -->
{% for post in site.thangNotes reversed %}
  {% include archive-single.html %}
{% endfor %}
