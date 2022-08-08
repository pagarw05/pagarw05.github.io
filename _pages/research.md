---
layout: archive
title: "Research Interests"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---
## <font color="#C69214"><b>Methodological</b></font>
Data Science, Data Analytics, Statistical Modeling, Game Theory, Risk Analysis, Decision Analysis, Operations Research

## <font color="#C69214"><b>Application</b></font>
Disaster Management, Homeland Security, Social Media Analytics, Risk Communication, Supply Chain, Health Care, Energy, Sustainability, Sports Analytics


## <font color="#154734"><b>Selected Research Areas</b></font>
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
