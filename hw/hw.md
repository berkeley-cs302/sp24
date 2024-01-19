---
lang: en
title: Test Homework
number: 1
layout: hw
hw: page.homework
---

{% assign hw = site.assignments[0] %}

{% include dates.html hw=hw %}


{{ hw.due_date }}


{{ page.number }}
{{ site.assignments[{{ page.number }}] }}


num 2 due date
{{ site.assignments[1].due_date }}
