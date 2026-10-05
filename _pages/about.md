---
permalink: /
title: ''
excerpt: ''
author_profile: true
redirect_from:
- /about/
- /about.html
ap_lang: en
ap_section: home
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<nav class="ap-contents" aria-label="On this page"><a href="#news" target="_self">News</a><a href="#publications" target="_self">Papers</a><a href="#honors-and-awards" target="_self">Honors</a><a href="#educations" target="_self">Education</a><a href="#invited-talks" target="_self">Invited Talks</a></nav>
<span class='anchor' id='about-me'></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">👨‍🏫 About Me</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 200px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

I am currently a Professor and Associate Head of the Department of Computer Science and Technology at [Guangdong University of Technology (GDUT)](https://www.gdut.edu.cn/). I received my B.Eng. degree from [South China University of Technology (SCUT)](https://www.scut.edu.cn/new/) in 2013, followed by M.Sc. and Ph.D. degrees from [Hong Kong Baptist University (HKBU)](https://www.hkbu.edu.hk/en.html) in 2014 and 2019, respectively, supervised by [Yiu-ming Cheung (张晓明)](https://www.comp.hkbu.edu.hk/~ymc/) (IEEE/AAAS/IAPR Fellow, Changjiang Chair Professor, Chair Professor in Artificial Intelligence@HKBU). Following a postdoctoral fellowship at HKBU in 2019, I joined GDUT in 2020, where I was promoted to Associate Professor in 2022 and Professor in 2026.

My research focuses on **Machine Learning** (ML) and **Data Science**. Specifically, I collaborate closely with [Yang Lu (卢杨)](https://jasonyanglu.github.io/) and [Mengke Li (李梦柯)](https://keke921.github.io/) on research topics including: **ML on Heterogeneous Data**, **Unsupervised Federated Learning**, **Non-stationary Data Analysis**. My research interests also inclue Large Language Models (LLMs) and AI for Science (AI4S). I have published {{ site.data.academic_profile.metrics.publications_total.en_phrase }} in journals and conferences, including those in **TPAMI, TCYB, TNNLS, SIGMOD, SIGKDD, NeurIPS, ICML, and AAAI**, to name a few. My publications include **two ESI Highly Cited Papers** and **one ESI Hot Paper**.

<!--
<a href='https://scholar.google.com/citations?user=EnqM5F4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
<a href='https://scholar.google.com/citations?user=EnqM5F4AAAAJ' target='_blank'><img src="https://img.shields.io/badge/citations-805-9cf?logo=Google%20Scholar&labelColor=f6f6f6&style=flat"></a>
-->

Currently, I serve as an **Associate Editor** for the *IEEE Transactions on Emerging Topics in Computational Intelligence* (TETCI). My academic and teaching contributions have been recognized with the Second Prize of the Guangdong Provincial Science and Technology Progress Award (2023), several Best Paper Awards (ISMIS’18, DOCS’24, 2020 IEEE CIS), and the MOE-Huawei "Intelligent Base" Pioneer Teacher Award.


<span class='anchor' id="news"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">🔥 News</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 200px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>
{{ site.data.academic_news.markdown }}

<p>For more news, please click <a href="/news/" target="_self">here</a>.</p>

<span class='anchor' id="publications"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">📝 Publications</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 200px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">ML on Heterogeneous Data</div><img src='images/Het-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **Heterogeneous Feature Data Cluster Analysis**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGMOD'26</span>](https://dl.acm.org/doi/abs/10.1145/3769772)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://ojs.aaai.org/index.php/AAAI/article/view/40104)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICDCS'24</span>](https://arxiv.org/abs/2601.16491)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'20</span>](https://ojs.aaai.org/index.php/AAAI/article/view/6168)

- **Heterogeneous Feature Data Representation Learning**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'24</span>](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'23</span>](https://ieeexplore.ieee.org/abstract/document/9887970)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span>](https://www.comp.hkbu.edu.hk/~ymc/papers/journal/TPAMI-2021-3056510-publication-version.)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IJCAI'22</span>](https://www.ijcai.org/proceedings/2022/522)
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">Unsupervised Federated Learning</div><img src='images/Fed-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **Federated Cluster Analysis**<br>
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://arxiv.org/abs/2601.17512)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
INS'25</span>](https://arxiv.org/abs/2603.12684)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
DOCS'24</span>](https://yqzhang-zz.github.io/zh-publications/papers/DOCS-24-FedCCL.pdf)

- **Heterogeneous Federated Learning**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
CVPR'26</span>](https://arxiv.org/abs/2605.02247)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
CVPR'25</span>](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mind_the_Gap_Confidence_Discrepancy_Can_Guide_Federated_Semi-Supervised_Learning_CVPR_2025_paper.html)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'25</span>](https://ebooks.iospress.nl/volumearticle/75876)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/10373104)

  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">Non-stationary Data Analysis</div><img src='images/NSD-Analysis.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **Time-series Data Analysis and Applications**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'26</span>](#)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://ojs.aaai.org/index.php/AAAI/article/view/39777)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
BIBM'25</span>](https://arxiv.org/abs/2510.12214)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'23</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA230625)

- **Streaming Data & Concept Drift Analysis**<br>
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'26</span>](https://arxiv.org/abs/2603.06757)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://arxiv.org/abs/2404.09243)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
  
</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">大语言模型应用</div><img src='images/Het-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **大语言模型提示调谐**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.09049)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'24</span>](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IJCAI'22</span>](https://www.ijcai.org/proceedings/2022/522)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ESWA'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0957417425003604)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'23</span>](https://ieeexplore.ieee.org/abstract/document/9887970)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span>](https://ieeexplore.ieee.org/abstract/document/9346004)

- **大语言模型表征增强**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGMOD'26</span>](https://dl.acm.org/doi/abs/10.1145/3769772)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICASSP'25</span>](https://ieeexplore.ieee.org/abstract/document/10889806)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'24</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA240709)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'22</span>](https://ieeexplore.ieee.org/abstract/document/9079460)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'20</span>](https://ieeexplore.ieee.org/abstract/document/8671525)

- **大语言模型综述**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #e3f2fd; color: #0b5394; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICDCS'24</span>](https://ieeexplore.ieee.org/abstract/document/10631083)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://ieeexplore.ieee.org/abstract/document/11300877)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/11007519)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'25</span>](https://ieeexplore.ieee.org/abstract/document/11134305)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'18</span>](https://ieeexplore.ieee.org/abstract/document/8423698)
  
</div>
</div>
-->
<br>
**List of Representative Publications**

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGMOD'27</span> 
[{{ site.data.academic_publications_by_id.C062.title }}](/zh-publications/#paper-C062)<br>
{{ site.data.academic_publications_by_id.C062.authors_markdown }}

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGMOD'26</span> 
[{{ site.data.academic_publications_by_id.C048.title }}]({{ site.data.academic_publications_by_id.C048.link }})<br>
{{ site.data.academic_publications_by_id.C048.authors_markdown }}

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
AAAI'26</span> 
[{{ site.data.academic_publications_by_id.C044.title }}]({{ site.data.academic_publications_by_id.C044.link }})<br>
{{ site.data.academic_publications_by_id.C044.authors_markdown }}

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGKDD'24</span> 
[{{ site.data.academic_publications_by_id.C018.title }}]({{ site.data.academic_publications_by_id.C018.link }})<br>
{{ site.data.academic_publications_by_id.C018.authors_markdown }}

- <span style="background-color: #e3f2fd; color: #0b5394; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
NeurIPS'24</span> 
[{{ site.data.academic_publications_by_id.C026.title }}]({{ site.data.academic_publications_by_id.C026.link }})<br>
{{ site.data.academic_publications_by_id.C026.authors_markdown }}

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TMM'26</span> 
[{{ site.data.academic_publications_by_id.J025.title }}]({{ site.data.academic_publications_by_id.J025.link }})<br>
{{ site.data.academic_publications_by_id.J025.authors_markdown }}

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TAI'25</span> 
[{{ site.data.academic_publications_by_id.J023.title }}]({{ site.data.academic_publications_by_id.J023.link }})<br>
{{ site.data.academic_publications_by_id.J023.authors_markdown }}

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span> 
[{{ site.data.academic_publications_by_id.J022.title }}]({{ site.data.academic_publications_by_id.J022.link }})<br>
{{ site.data.academic_publications_by_id.J022.authors_markdown }}

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span> 
[{{ site.data.academic_publications_by_id.J017.title }}]({{ site.data.academic_publications_by_id.J017.link }})<br>
{{ site.data.academic_publications_by_id.J017.authors_markdown }}

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span> 
[{{ site.data.academic_publications_by_id.J005.title }}]({{ site.data.academic_publications_by_id.J005.link }})<br>
{{ site.data.academic_publications_by_id.J005.authors_markdown }}

  ... ... For a full list of publications, you can click <a href="/zh-publications/" target="_self">here</a> or please visit [DBLP](https://dblp.org/pid/125/5587-6.html)  &#124; [Google Scholar](https://scholar.google.com/citations?user=EnqM5F4AAAAJ&hl) ... ...

<span class='anchor' id="honors-and-awards"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">🏆 Honors & Awards</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 200px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>
- *2026/06*: IEEE TETCI Outstanding Associate Editor Performance Award
- *2026/03*: Outstanding Advisor for Innovation and Entrepreneurship Education, Guangdong University of Technology
- *2026/01*: Outstanding Postgraduate Supervisor, Guangdong University of Technology
- *2025/12*: Outstanding Editorial Board Member, Journal of Guangdong University of Technology
- *2024/12*: Excellent Reviewer, ACM SIGKDD 2025
- *2024/08*: Second Prize of Guangdong Provincial Science and Technology Progress Award (2023)
- *2024/08*: Best Paper Award, The 6th IEEE International Conference on Data-driven Optimization of Complex Systems (DOCS 2024)
- *2022/09*: MOE-Huawei "Intelligent Base" Pioneer Teacher Award
- *2021/06*: First Prize, Young Teachers' Teaching Competition, School of Computer Science, Guangdong University of Technology
- *2019/12*: Research Performance Award, Department of Computer Science, Hong Kong Baptist University
- *2019/08*: Champion, Postgraduate Research Paper Competition, IEEE Computational Intelligence Society (CIS) Hong Kong Chapter
- *2018/10*: Best Student Paper Award, The 24th International Symposium on Methodologies for Intelligent Systems (ISMIS 2018), Springer
- *2014/06*: Merit Scholarship, Department of Computer Science, Hong Kong Baptist University
- *2014/01*: Merit Scholarship, Department of Computer Science, Hong Kong Baptist University



<span class='anchor' id="educations"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">👨‍🎓 Educations</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 200px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>
- *{{ site.data.academic_profile.education["edu-1"].start | replace: "-", "/" }} - {{ site.data.academic_profile.education["edu-1"].end | replace: "-", "/" }}*: Ph.D. in Computer Science, Hong Kong Baptist University 
<br><span style="font-size: 0.85em; color: #666;">(Supervisor: Yiu-ming Cheung (Chair Professor, IEEE Fellow, AAAS Fellow, and IAPR Fellow)</span>
- *{{ site.data.academic_profile.education["edu-2"].start | replace: "-", "/" }} - {{ site.data.academic_profile.education["edu-2"].end | replace: "-", "/" }}*: M.Sc. in Computer Science, Hong Kong Baptist University
- *{{ site.data.academic_profile.education["edu-3"].start | replace: "-", "/" }} - {{ site.data.academic_profile.education["edu-3"].end | replace: "-", "/" }}*: B.Eng. in Biomedical Engineering, South China University of Technology
- *{{ site.data.academic_profile.education["edu-4"].start | replace: "-", "/" }} - {{ site.data.academic_profile.education["edu-4"].end | replace: "-", "/" }}*: Science Class, Shenzhen Hongling High School

<span class='anchor' id="invited-talks"></span>

<h1 style="border-bottom: none; margin-bottom: 8px; padding-bottom: 0;">💬 Invited Talks</h1>
<div style="display: flex; align-items: flex-end; margin-top: 4px; margin-bottom: 20px;">
  <div style="width: 200px; height: 3px; background-color: #1A365D;"></div>
  <div style="flex-grow: 1; height: 1px; background-color: #1A365D;"></div>
</div>

- *2026/05*: Reshaping Higher Education and Innovation in the Era of Large Language Models, Hong Kong Huashang Science & Education Group
- *2025/12*: Clustering Analysis of Complex Distributed Data under Dynamic Environments, Shanxi University (SXU)
- *2024/12*: Clustering Complex Data Under Dynamic Environments, Northeastern University (NEU) / State Key Laboratory of Synthetical Automation for Process Industries
- *2024/12*: Clustering Analysis of Complex Data under Dynamic Environments, Guangdong University of Technology (GDUT)
- *2023/11*: Learning from Complex Data with Cross-Coupled Heterogeneous Attributes, Southern University of Science and Technology (SUSTech)
- *2021/04*: Insights into AI Research: A Dual Perspective from Authors and Reviewers, Guangdong University of Technology (GDUT)
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<div style="margin-top: 60px;">
  
  <div style="height: 1px; background: linear-gradient(to right, transparent, #cbd5e1, transparent);"></div>

  <div style="background: linear-gradient(to right, transparent, rgba(241, 245, 249, 0.8), transparent); padding: 40px 0 30px 0;">
    
    <div style="display: flex; justify-content: center; align-items: center; flex-wrap: wrap; gap: 50px;">
      
      <div style="text-align: left; line-height: 1.8;">
        
        <div style="font-weight: bold; font-size: 1.1em; margin-bottom: 5px; color: #4b5563;">
          📊 Visitor Statistics
        </div>
        
        <div style="color: #64748b; font-size: 0.9em;">
          <script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
          <span id="busuanzi_container_site_pv" style="display:none;">
            👀 Total Visits: <span id="busuanzi_value_site_pv" style="font-weight: bold; color: #475569;"></span>
          </span>
        </div>
        
        <div style="color: #94a3b8; font-size: 0.85em; margin-top: 2px;">
          © {{ site.time | date: "%Y" }} Yiqun Zhang. All rights reserved.<br>
          Last updated: {{ site.time | date: "%B %Y" }}.
        </div>
        
      </div>

      <div style="width: 100px; opacity: 0.9;"> 
        <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=lPtt2sUwH1MwEnQW4pcHVaruKWdriQxF0N9KIeqgnws"></script>
      </div>

    </div>
  </div>
</div>

