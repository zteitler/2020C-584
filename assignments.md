---
layout: page
title: Assignments
---

## Assignments

### Homework

{% assign hwbydue = site.hw | sort: "duedate" %}

{% for homework in hwbydue -%}

| [{{ homework.title }}]({{site.baseurl}}{{ homework.url }}) | Due: {{ homework.duedate | date_to_string: "ordinal", "US"  }} |
{% endfor %}


### Papers

{% assign papersbydue = site.papers | sort: "duedate" %}

{% for paper in papersbydue -%}

| [{{ paper.title }}]({{ site.baseurl }}{{ paper.url }}) | Due: {{ paper.duedate | date_to_string: "ordinal", "US"  }} |
{% endfor %}


### Template

[LaTeX template for homework](assets/584-Homework-template.tex)
