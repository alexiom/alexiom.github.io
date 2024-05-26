---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
redirect_from: /research/
---

My current research interests include forecasting intermittent demand, airline upgrade auctions, and empirically defining markets. 

Working Papers
---
1. [``What Can Web Traffic Reveal about Air-Travel Demand?"](http://alexmarsh.io/files/MarshScottVanKuikenWilliams2024.pdf) with Garrett Scott, Drew Van Kuiken, and Jonathan W. Williams. *Submitted to Economics of Transportation*
2. ``Revenue Management with Reallocation" with Garrett Scott and Jonathan W. Williams
3. ``Allocating Upgrades: Challenges and Opportunities in the Airline Industry" with Garrett Scott and Jonathan W. Williams


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
