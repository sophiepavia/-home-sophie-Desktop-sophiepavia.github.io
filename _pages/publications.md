---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
2023
----
1. **"Microtransit Optimizer for Mobility-on-Demand"**\
Michael Wilbur, Sophie Pavia, Abhishek Dubey, Pravesh Koirala, Zakariyya Al-Quran, Maxime R Coursey, Philip Pugliese, Accepted at IEEE International Conference on Smart Computing (SMARTCOMP) 2023 **Best Demo Award**
2. **"Learning Circular Tabular Embeddings for Heterogeneous Large-scale Structured Datasets"**\
Michael Gubanov, Anna Pyayt, Sophie Pavia, to appear in EDBT, DOLAP 2023

2022
----
1. [**"Visualizing and Querying Large-scale Structured Datasets by Learning Multi-layered 3D Meta-Profiles"**](https://ieeexplore.ieee.org/document/10020546)\
Michael Gubanov, Anna Pyayt, Sophie Pavia in IEEE BigData, 2022
2. [**"Leveraging Scalable Profiling to Learn and Visualize the Latest Trustworthy COVID-19 Medical Research Findings"**](https://dl.acm.org/doi/abs/10.1145/3511808.3557171)\
Michael Gubanov, Sophie Pavia, Anna Pyayt, William Goble, in ACM CIKM, 2022
3. [**"Simplifying Access to Large-scale Structured Datasets by Meta-Profiling with Scalable Training Set Enrichment"**](https://dl.acm.org/doi/pdf/10.1145/3514221.3520156)\
Sophie Pavia, Rituparna Khan, Anna Pyayt, Michael Gubanov, in ACM SIGMOD, 2022
4. [**"Hybrid Metadata Classification in Large-scale Structured Datasets"**](https://www.rintonpress.com/xjdi3/xjdi3-4/460-473.pdf)\
Sophie Pavia, Nick Piraino, Kazi Islam, Anna Pyayt, Michael Gubanov, invited paper in the journal of Data Intelligence, Rinton Press, Special Issue on "Best of DEXA", 2022

2021
----
1. [**"Towards Unveiling Dark Web Structured Data"**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9671367)\
Sophie Pavia, Rituparna Khan, Anna Pyayt, Michael Gubanov, in IEEE BigData, 2021
2. [**"Learning Tabular Embeddings at Web Scale"**](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9671717)\
Sophie Pavia, Rituparna Khan, Anna Pyayt, Michael Gubanov, in IEEE BigData, 2021

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
