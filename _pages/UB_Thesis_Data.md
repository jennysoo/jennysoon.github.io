---
layout: archive
title: "UB M.Sc. Thesis Data"
permalink: /UB_Thesis_Data/
author_profile: true

---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
