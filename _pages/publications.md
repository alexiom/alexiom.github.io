---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
redirect_from: /research/
---

My current research interests include forecasting intermittent demand, airline upgrade auctions, and empirically defining markets. 

Current Projects
---

1. Forecasting Intermittent Demand
2. Airline Upgrade Auctions
3. Empirically Defining Markets

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
