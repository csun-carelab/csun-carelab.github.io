---
title: Research
nav:
  order: 1
  tooltip: Research directions of our lab!
---

# {% include icon.html icon="fa-solid fa-road" %}Research Directions

Each of our projects focuses on one or more of three elements: the *robot*, the *algorithm* that drives the robot, or the *human* that interacts with the robot. You can click on any of the buttons below to sort our research based its key element.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Current

{% include list.html component="card" data="projects" filter="group == 'current'" %}

{% include section.html %}

## Previous

{% include list.html component="card" data="projects" filter="!group" style="small" %}
