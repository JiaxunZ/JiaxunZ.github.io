---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

Hi! I'm Jiaxun Zhang, an undergraduate student at the [University of Illinois at Urbana-Champaign](https://illinois.edu/). I am fortunate to be advised by [Prof. Ismini Lourentzou](https://isminoula.github.io), [Prof. Jiaxuan You](https://cs.stanford.edu/~jiaxuan/), and [Prof. Koustuv Saha](https://koustuv.com). My research interests lie in large language models, AI agents, and their applications.

## 📢 News
- [Feb 2026] 1 paper accepted to **CVPR 2026** (Findings)!
- [Jan 2026] 1 paper accepted to **ACM CHI 2026**!
- [Sep 2025] 1 paper accepted to **EMNLP 2025** (System Demonstrations)!
- [Aug 2025] 1 paper accepted to **EMNLP 2025**!

## 📄 Pre-prints

<div class="pub-list">{% for post in site.publications reversed %}{% if post.category == "preprints" %}{% include pub-card.html %}{% endif %}{% endfor %}</div>

## 📄 Publications 
<p style="font-size:0.85em; color:#666;">* denotes equal contribution</p>

<div class="pub-list">{% for post in site.publications %}{% unless post.category == "preprints" %}{% include pub-card.html %}{% endunless %}{% endfor %}</div>

{% comment %}
## Teaching

<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
{% endcomment %}

## 🎓 Education

- B.S. in Statistics & Computer Science, University of Illinois at Urbana-Champaign, 2022–present

## Awards

- Fiddler Innovation Undergraduate Student Fellowship Award, UIUC, 2025
- Dean's List — Fall 2022, Spring 2023, Spring 2024, Spring 2025
