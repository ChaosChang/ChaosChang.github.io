---
permalink: /
title: "Profile"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## Short bio
Hengyuan Chang is a researcher at the Japan Advanced Institute of Science and Technology [JAIST](https://www.jaist.ac.jp/). He received Ph.D. in information science in [Human-Centered AI Laboratory](https://www.jaist.ac.jp/~xie/lab.html), JAIST, Ishikawa, Japan, supervised by Prof. Haoran Xie.
He received his bachelor's degree in computer science at Donghua University, Shanghai, China, and his master degree in information science at JAIST, Ishikawa, JAPAN. His research lies at the intersection of image&video generation and fluid dynamics.

---
## Research Interests
**Image and video generation** with hand-drawn sketch guidance

**Physics-informed** generation

**Fluid data analysis**  and simulation

---
## Selected Publications

{% assign selected_pubs = site.publications | sort: "index" %}
{% for post in selected_pubs limit: 20 %} 
### [{{ post.title }}]({{ post.url | relative_url }}) 
{% if post.preview %} ![{{ post.title }}]({{ post.preview | relative_url }}) 
{% endif %} 
{% if post.authors%} {{ post.authors | markdownify }}
{% endif %} 
**{{ post.venue }}**, {{ post.date | date: "%Y" }} 
{% if post.paperurl %} [Paper]({{ post.paperurl }}) 
{% endif %} 
{% if post.codeurl %} [Code]({{ post.codeurl }}) 
{% endif %} 
{% endfor %}

- Sketch-Guided Flow Field Generation with Diffusion Model. International Workshop on Advanced Image Technology 2024.


---
## Experiences
2025.05 - 2026.02, Collaboration Research (remote), [ANIMINS](https://www.meti.go.jp/policy/mono_info_service/geniac/selection_data_2/index.html), [OLM, Digital, Inc](https://www.olm.co.jp/rd), Japan.

2018.11 - 2020.02, research student, Tokyo Metropolitan University, Japan.

---
## Educations
Ph.D. in Information Science, JAIST, Japan (2022.04 – 2026.03)

M.S. in Information Science, JAIST, Japan (2020.04 – 2022.03)

B.E. in Computer Science, Donghua University, China (2014.09 – 2018.06)

