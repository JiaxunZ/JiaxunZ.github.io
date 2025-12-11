---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**University of Illinois at Urbana-Champaign**  
B.S. in Statistics & Computer Science | Expected May 2026  
GPA: 3.94/4.00

**Relevant Coursework:**
- *Computer Science:* Machine Learning, Natural Language Processing, Deep Learning for Computer Vision, Data Mining, Machine Learning Systems, Algorithms, Numeric Methods
- *Math & Statistics:* Statistical Modeling, Applied Bayesian Analysis, Statistics and Probability, Linear Algebra

## Awards & Honors

- **Fiddler Innovation Undergraduate Student Fellowship Award**, UIUC, 2025
- **Dean's List** — Fall 2022, Spring 2023, Spring 2024, Spring 2025

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
