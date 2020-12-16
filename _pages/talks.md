---
layout: archive
title: "Talks"
permalink: /talks/
author_profile: false
---

{% include base_path %}

{% for post in site.talks reversed %}
  talk {{post}}  
{% endfor %}
