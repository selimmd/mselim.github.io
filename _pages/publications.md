---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my detail articles list on Google Scholar profile [link](https://scholar.google.com/citations?user=lx7UxJcAAAAJ&hl=en)</div>
{% endif %}

%{% include base_path %}

%{% for post in site.publications reversed %}
%  {% include archive-single.html %}
%{% endfor %}
