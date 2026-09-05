---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

<!-- Hi! I'm Jiaxun Zhang, an undergraduate student at the [University of Illinois at Urbana-Champaign](https://illinois.edu/). I am fortunate to be advised by [Prof. Ismini Lourentzou](https://isminoula.github.io), [Prof. Jiaxuan You](https://cs.stanford.edu/~jiaxuan/), and [Prof. Koustuv Saha](https://koustuv.com). My research interests lie in large language models, AI agents, and their applications. -->

Hi! I'm Jiaxun Zhang, a first-year PhD student in Computer Science and Engineering at the [University of California, San Diego](https://ucsd.edu), advised by [Prof. Jingbo Shang](https://shangjingbo1226.github.io). Previously, I graduated from the [University of Illinois at Urbana-Champaign](https://illinois.edu/), where I was fortunate to work with [Prof. Ismini Lourentzou](https://isminoula.github.io), [Prof. Jiaxuan You](https://cs.stanford.edu/~jiaxuan/), and [Prof. Koustuv Saha](https://koustuv.com). My research interests lie in large language models, AI agents, and their applications.

I am always happy to chat and open to research collaborations. Feel free to reach out!

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

- Ph.D. in Computer Science and Engineering, University of California, San Diego, 2026–present
- B.S. in Statistics & Computer Science, University of Illinois at Urbana-Champaign, 2022–2026

## Awards

- Jacobs School of Engineering Fellowship, UCSD, 2026
- Fiddler Innovation Undergraduate Student Fellowship, UIUC, 2025
- Dean's List — Fall 2022, Spring 2023, Spring 2024, Spring 2025
