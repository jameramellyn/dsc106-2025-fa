---
layout: page
title: 📺 Final Project Showcase
description: Showcase of student final projects from Spring 2025.
nav_order: 1
---

# Final Project Showcase

This page lists all projects submitted by the 130 students in Fall 2025's
offering of DSC 106. Projects are listed with the permission of the
student teams.

There were four kinds of awards given to student submissions:

1. The Best Project Award was given to the top 3 submissions based on the
   effectiveness and creativity of the project visualizations.
1. The Best Presentation Award was given to the top 4 submissions based on
   the quality of the project video and presentation during the showcase.
1. The Honorable Mention Award was given to the top 3 submissions (after the
   Best Project Awards) based on effectiveness and creativity of the project
   visualizations.
1. The People's Choice Award was given to the top 5 submissions based on
   votes cast during the in-person showcase event.

{% for project in site.data.projects %}
{% include project-showcase-card.html project=project %}
{% endfor %}
