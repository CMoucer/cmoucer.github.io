---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022, 2021]
abbr: [preprint]
nav: true
nav_order: 1
---

**codes ---** see my [github](https://github.com/CMoucer) profile. The python package PEPit for numerical worst-case analyses is available [here](https://github.com/PerformanceEstimation/PEPit) and its documentation [here](https://pepit.readthedocs.io/en/latest/).

**talks ---** here is a selection of slides from previous presentations:
+ 07/2022: **PEPit: a python package for worst-case analysis of first-order optimization methods and their continuous versions**, ICCOPT, ([slides](https://github.com/CMoucer/PEP_ODEs/blob/master/presentation_iccopt.pdf))
+ 11/2021: **Vers une IA plus frugale**, talk at [IHP](https://www.ihp.fr/fr) for the [IAPlusK](https://indico.math.cnrs.fr/event/6681/) seminar


<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.abbr %}
  <h2 class="status">{{y}}s</h2>
  {% bibliography -f papers -q @*[abbr={{y}}]* %}
{% endfor %}

</div>



