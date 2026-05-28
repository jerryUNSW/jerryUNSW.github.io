---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Yizhang He is currently an associate professor at the Global College of Shanghai Jiao Tong University. Before joining SJTU, he was an Associate Lecturer (Teaching & Research) in the School of Computer Science and Engineering at University of New South Wales from 2025 to 2026, and a Postdoctoral Fellow at UNSW in 2025. He got his Ph.D. in Computer Science from UNSW in 2025 and his bachelor's degree in Data Science from UNSW in 2019.

His research interests lie in **graph mining**, **privacy-preserving computation**, and **large language models**. In particular, he works on cohesive subgraph discovery, motif counting, and differential privacy for large-scale graph analytics. Link to [Google Scholar](https://scholar.google.com/citations?user=AeA4sfcAAAAJ). Email: yizhang.he@unsw.edu.au.

---

## News

- **Jun 2026**: Joined Shanghai Jiao Tong University as Associate Professor in the Global College.
- **May 2026**: One paper submitted to EMNLP 2026.
- **2025**: Three papers accepted at SIGMOD 2025, one at ICDE 2025, one at TKDE 2025.
- **2024**: One paper accepted at VLDBJ, one at ICDE 2024.
- **2023**: One paper accepted at SIGMOD 2023.
- **2022**: One paper accepted at ICDE 2022.

---

## <span id="publications">Publications</span>

Also available on [Google Scholar](https://scholar.google.com/citations?user=AeA4sfcAAAAJ).

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---

## <span id="teaching">Teaching</span>

{% for post in site.teaching %}
  {% include archive-single.html %}
{% endfor %}

---

## <span id="service">Academic Service</span>

- **Reviewer**: ICDE, SIGMOD, VLDBJ, TKDE
