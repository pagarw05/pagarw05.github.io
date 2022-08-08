---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

For a complete list of my publications, please see <a href="https://scholar.google.com/citations?user=nxJCrkUAAAAJ&hl=en" style="color: #FF6A39; font-weight:bold">my Google Scholar profile</a>.
<hr>

[//]: # (<sup>*</sup> Equal authorship, <sup>+</sup> Student author)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


