---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles and preprint on [my Google Scholar profile](https://scholar.google.com/citations?user=G1WQQN4AAAAJ&hl=en)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
