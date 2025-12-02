---
layout: page
permalink: /publications/
title: Publications 📜
description:
  My scientific publications and theses until 2022.
  <b>For more up to date information, please visit my <a href="https://scholar.google.com/citations?user=TOu-cpQAAAAJ" target="_blank">Google Scholar profile</a>.</b>
years: [2019, 2020, 2021, 2022]
files: ["papers.bib", "theses.bib"]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->
<div class="publications">

{% assign sorted_years = page.years | sort | reverse %}
{% for y in sorted_years %}
  <h2 class="year">{{y}}</h2>
  {% for file in page.files %}
    {% bibliography -f {{file}} -q @*[year={{y}}]* %}
  {% endfor %}
{% endfor %}

</div>
