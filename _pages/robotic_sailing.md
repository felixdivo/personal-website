---
layout: page
title: Robotic Sailing ⛵
permalink: /robotic_sailing/
nav: true
# description: ""  # Not properly formatted
display_categories: [work, fun]
horizontal: false
---

Since 2016, I am an active member of the [Sailing Team Darmstadt e.V.](https://www.st-darmstadt.de/) (est. 2008),
which is a non-profit student group based in at the [TU Darmstadt, Germany](https://www.tu-darmstadt.de/).
Our goal is to develop fully autonomous sailing boats capable of navigating the open sea.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ site.baseurl }}/assets/img/stda_2020_oct.jpg" data-zoomable>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ site.baseurl }}/assets/img/stda_2021_jul.jpg" data-zoomable>
    </div>
</div>

<small style="font-weight: lighter">
<br/>
With kind permission from © Sailing Team Darmstadt e.V.
More images can be found on Instagram: [*@sailingteam_darmstadt*](https://www.instagram.com/sailingteam_darmstadt/).
</small>

## Software Contributions

Over the years, I spent countless hours developing software for the boat(s).
While starting out as a small tinkering project, we steadily grew it into a rather professional-like development effort driven by the growth in memberships.
One of my main contributions there were the modularization of the large codebase that has grown over the years
and the introduction of clear quality principles supported by extensive [CI tools](https://docs.gitlab.com/ee/ci/).
Additionally, I developed (mostly in [Python](https://www.python.org/)):

- A foundational library for working with cartesian (`x, y`) and polar (`latitude, longitude`) geometries.
- Import and transformation of various data formats, like [nautical navigation charts (ENCs)](https://en.wikipedia.org/wiki/Electronic_navigational_chart) and [topography data](https://www.asg.ed.tum.de/iapg/forschung/topographie/earth2014/).
- Tools for creating globe-spanning navigation graphs and augmenting them with datasets.
- A system for managing [local tangent plane coordinates (LTPs)](https://en.wikipedia.org/wiki/Local_tangent_plane_coordinates) and object permanence.
- Interfacing with [hardware](https://www.st-darmstadt.de/ueber-uns/boote/), among others using the [python-can](https://pypi.org/project/python-can/) library of which I am now [one of the core developers](https://github.com/hardbyte/python-can/graphs/contributors).
- A novel tool for writing declarative test cases for [ROS2](https://docs.ros.org/en/rolling/).
- [Property-based](https://hypothesis.works/) and [mutation](https://mutmut.readthedocs.io/en/latest/) testing.
- A lot of infrastructure and tooling behind the scenes.
- More …

Most of the code is internal as of now but will be open-sourced soon.

## Member of the board

In addition to the technical contributions above, I also led the team in various ways over the years, including by:
daily operations,
membership recruitment,
finance and [sponsorings](https://www.st-darmstadt.de/partner/sponsoren-prototyp-ii/),
multiple [fair exhibitions](https://www.st-darmstadt.de/2019/04/hannover-messe-2019-2/),
and strategic decisions.

- 2017 — 2019: Treasurer (*Finanzvorstand*)
- 2019 — 2020: Vice Chairperson (*2. Vorsitzender*)
- 2020 — 2022: Chairperson (*1. Vorsitzender*)
- 2022 — now: Member of the board (*Beisitzer*)
