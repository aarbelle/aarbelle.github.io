---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

For a full list of my publications visit <u><a href="https://scholar.google.co.uk/citations?user=uU_V_PsAAAAJ&hl=en">my Google Scholar profile</a>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
