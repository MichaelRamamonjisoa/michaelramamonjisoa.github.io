---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
