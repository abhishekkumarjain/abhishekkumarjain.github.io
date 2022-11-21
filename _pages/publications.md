---
layout: single
title: "Publications"
permalink: /publications/
author_profile: true
---
Below you will find a list of my publications and links to download them. Note that they are provided here to ensure timely dissemination of scholarly and technical work. Copyright and all rights therein are retained by authors or by other copyright holders.

You can also view my [Google Scholar](https://scholar.google.com/citations?user=k8kthdkAAAAJ&hl=en),  and [ORCID](https://orcid.org/0000-0003-3797-029X) Profiles

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
