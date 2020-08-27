---
layout: page
title: Assignments
---

## Assignments

### Homework

{% assign hwbydue = site.hw | sort: "duedate" | reverse %}

{% for homework in hwbydue %}

[{{ homework.title }}]({{ homework.url }})
Due: {{ homework.duedate | date_to_string: "ordinal", "US"  }}

{% endfor %}


### Template

[LaTeX template for homework](assets/584-Homework-template.tex)
