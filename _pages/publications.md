---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a full list of my work on [NASA ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0002-9986-4604&sort=date+desc).
Below are my publications:

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}