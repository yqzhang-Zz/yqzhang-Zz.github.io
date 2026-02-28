---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

# 👨‍🏫 About Me

I am currently a Professor and Associate Head of the Department of Computer Science and Technology at [Guangdong University of Technology (GDUT)](https://www.gdut.edu.cn/). I received my B.Eng. degree from [South China University of Technology (SCUT)](https://www.scut.edu.cn/new/) in 2013, followed by M.Sc. and Ph.D. degrees from [Hong Kong Baptist University (HKBU)](https://www.hkbu.edu.hk/en.html) in 2014 and 2019, respectively, supervised by [Yiu-ming Cheung (张晓明)](https://www.comp.hkbu.edu.hk/~ymc/) (IEEE/AAAS/IAPR Fellow, Changjiang Chair Professor, Chair Professor in Artificial Intelligence). Following a postdoctoral fellowship at HKBU in 2019, I joined GDUT in 2020, where I was promoted to Associate Professor in 2022 and Professor in 2026.

My research focuses on **Machine Learning** (ML) and **Data Science**. Specifically, I collaborate closely with [Yang Lu (卢杨)](https://jasonyanglu.github.io/), Mengke Li (李梦柯), and [Yuzhu Ji (姬玉柱)](https://andrewchiyz.github.io/) on research topics including: **ML on Heterogeneous Data**, **Unsupervised Federated Learning**, **Non-stationary Data Analysis**. My research interests also inclue Large Language Models (LLMs) and AI for Science (AI4S). I have published over 90 papers in top-tier journals and conferences, including those in **TPAMI, TNNLS, TIP, TMM, TCYB, SIGMOD, SIGKDD, NeurIPS, CVPR, ICCV, AAAI, IJCAI, and ACM MM**.

<!--
<a href='https://scholar.google.com/citations?user=EnqM5F4AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.
<a href='https://scholar.google.com/citations?user=EnqM5F4AAAAJ' target='_blank'><img src="https://img.shields.io/badge/citations-805-9cf?logo=Google%20Scholar&labelColor=f6f6f6&style=flat"></a>
-->

Currently, I serve as an **Associate Editor** for the *IEEE Transactions on Emerging Topics in Computational Intelligence* (TETCI). My academic and teaching contributions have been recognized with the Second Prize of the Guangdong Provincial Science and Technology Progress Award (2023), several Best Paper Awards (ISMIS’18, DOCS’24, 2020 IEEE CIS), and the MOE-Huawei "Intelligent Base" Pioneer Teacher Award.

<span style="color: red;">
Our **Open-environment Machine learning Group (OMG)** is constantly looking for self-motivated postgraduate and undergraduate students interested in scientific research. (For more details, please refer to [About OMG](/zh-OMG/)).</span>

<span class='anchor' id="news"></span>

# 🔥 News
- *2026/02*: &nbsp;🎉🎉 Two papers accepted to CVPR 2026, congratulations to Hezhao Liu and Shihao Hou!
- *2026/01*: &nbsp;🎉 One paper accepted as a long paper to DASFAA 2026, congratulations to Junyang Chen!
- *2026/01*: &nbsp;🎉 Two papers accepted to ICASSP 2026, congratulations to Shujie Qiu and Taixi Chen!
- *2026/01*: &nbsp;🎉🎉 The paper “[Learning Self-Growth Maps for…](https://ieeexplore.ieee.org/abstract/document/11007519)” (TNNLS, 2025) has been selected as a Highly Cited Paper by the ESI.
- *2025/12*: &nbsp;🎉 Two papers accepted by IoTJ.

<span class='anchor' id="publications"></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">ML on Heterogeneous Data</div><img src='images/Het-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **Heterogeneous Feature Representation Learning**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.09049)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'24</span>](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)
<!--
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IJCAI'22</span>](https://www.ijcai.org/proceedings/2022/522)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ESWA'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0957417425003604)
-->
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'23</span>](https://ieeexplore.ieee.org/abstract/document/9887970)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span>](https://ieeexplore.ieee.org/abstract/document/9346004)

- **Distance Metric for Heterogeneous Features**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGMOD'26</span>](https://dl.acm.org/doi/abs/10.1145/3769772)
<!--
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICASSP'25</span>](https://ieeexplore.ieee.org/abstract/document/10889806)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'24</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA240709)
-->
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'22</span>](https://ieeexplore.ieee.org/abstract/document/9079460)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'20</span>](https://ieeexplore.ieee.org/abstract/document/8671525)

- **Heterogeneous Distribution Learning**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
<!--
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICDCS'24</span>](https://ieeexplore.ieee.org/abstract/document/10631083)
-->
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://ieeexplore.ieee.org/abstract/document/11300877)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/11007519)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'25</span>](https://ieeexplore.ieee.org/abstract/document/11134305)
<!--
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'18</span>](https://ieeexplore.ieee.org/abstract/document/8423698)
-->
  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">Unsupervised Federated Learning</div><img src='images/Fed-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **Federated Cluster Analysis**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
DOCS'24</span>](https://ieeexplore.ieee.org/abstract/document/10704350)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IoTJ'26</span>](https://ieeexplore.ieee.org/abstract/document/11328086)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
INS'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0020025525010941)

- **Heterogeneous Federated Learning**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
CVPR'26</span>](xxx)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
CVPR'25</span>](https://openaccess.thecvf.com/content/CVPR2025/html/Liu_Mind_the_Gap_Confidence_Discrepancy_Can_Guide_Federated_Semi-Supervised_Learning_CVPR_2025_paper.html)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'25</span>](https://ebooks.iospress.nl/volumearticle/75876)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/10373104)

  
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">Non-stationary Data Analysis</div><img src='images/NSD-Analysis.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **Time-series Data Analysis**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.17008)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
BIBM'25</span>](https://arxiv.org/abs/2510.12214)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'23</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA230625)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
PRICAI'25</span>](https://arxiv.org/abs/2510.15985)

- **Streaming Data & Concept Drift Analysis**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TETCI'26</span>](https://ieeexplore.ieee.org/abstract/document/11134305)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span>](https://ieeexplore.ieee.org/abstract/document/11007519)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
  
</div>
</div>

<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge" style="font-size: 1.0em; font-weight: bold;">大语言模型应用</div><img src='images/Het-ML.png' alt="sym" width="100%"></div></div><div class='paper-box-text' markdown="1">
  
- **大语言模型提示调谐**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'26</span>](https://arxiv.org/abs/2511.09049)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGKDD'24</span>](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
IJCAI'22</span>](https://www.ijcai.org/proceedings/2022/522)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ESWA'25</span>](https://www.sciencedirect.com/science/article/abs/pii/S0957417425003604)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'23</span>](https://ieeexplore.ieee.org/abstract/document/9887970)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span>](https://ieeexplore.ieee.org/abstract/document/9346004)

- **大语言模型表征增强**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
SIGMOD'26</span>](https://dl.acm.org/doi/abs/10.1145/3769772)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ICASSP'25</span>](https://ieeexplore.ieee.org/abstract/document/10889806)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ECAI'24</span>](https://ebooks.iospress.nl/doi/10.3233/FAIA240709)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span>](https://ieeexplore.ieee.org/abstract/document/11274409)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'22</span>](https://ieeexplore.ieee.org/abstract/document/9079460)
[<span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'20</span>](https://ieeexplore.ieee.org/abstract/document/8671525)

- **大语言模型综述**<br>
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
AAAI'25</span>](https://ojs.aaai.org/index.php/AAAI/article/view/34429)
[<span style="display: inline-block; background-color: #e3f2fd; color: #1976d2; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
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

- <span style="background-color: #e3f2fd; color: #1976d2; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGMOD'26</span> 
[Categorical Data Clustering via Value Order Estimated Distance Metric Learning](https://dl.acm.org/doi/abs/10.1145/3769772)<br>
**Yiqun Zhang**, Mingjie Zhao, Hong Jia, Mengke Li, Yang Lu and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="background-color: #e3f2fd; color: #1976d2; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
CVPR'26</span> 
SECOS: Semantic Capture for Rigorous Classification in Open-World Semi-Supervised Learning<br>
Hezhao Liu, Jiacheng Yang, Junlong Gao, Mengke Li, **Yiqun Zhang**, Shreyank Gowda and Yang Lu<sup>&#x2709;</sup>

- <span style="background-color: #e3f2fd; color: #1976d2; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
AAAI'26</span> 
[Mask the Redundancy: Evolving Masking Representation Learning for Multivariate Time-Series Clustering](https://arxiv.org/abs/2511.17008)<br>
Zexi Tan, Xiaopeng Luo, Yunlin Liu and **Yiqun Zhang**<sup>&#x2709;</sup>

- <span style="background-color: #e3f2fd; color: #1976d2; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
SIGKDD'24</span> 
[QGRL: Quaternion Graph Representation Learning for Heterogeneous Feature Data Clustering](https://dl.acm.org/doi/abs/10.1145/3637528.3671839)<br>
Junyang Chen, Yuzhu Ji, Rong Zou, **Yiqun Zhang**<sup>&#x2709;</sup> and Yiu-ming Cheung

- <span style="background-color: #e3f2fd; color: #1976d2; padding: 2px 6px; border-radius: 4px; font-weight: bold; font-size: 0.9em; margin-right: 6px;">
NeurIPS'24</span> 
[Improving Visual Prompt Tuning by Gaussian Neighborhood Minimization for Long-Tailed Visual Recognition](https://proceedings.neurips.cc/paper_files/paper/2024/hash/bc667ac84ef58f2b5022da97a465cbab-Abstract-Conference.html)<br>
Mengke Li, Ye Liu, Yang Lu, **Yiqun Zhang**, Yiu-ming Cheung and Hui Huang<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TAI'25</span> 
[Trending Applications of Large Language Models: A User Perspective Survey](https://ieeexplore.ieee.org/abstract/document/11199892)<br>
**Yiqun Zhang**, Mingjie Zhao, Yunfan Zhang and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TCYB'25</span> 
[Online Heterogeneous Feature Selection](https://ieeexplore.ieee.org/abstract/document/11274409)<br>
**Yiqun Zhang**, Xinxi Chen, Lang Zhao, Yuzhu Ji, Peng Liu and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TNNLS'25</span> 
[Learning Self-Growth Maps for Fast and Accurate Imbalanced Streaming Data Clustering](https://ieeexplore.ieee.org/abstract/document/11007519)<br>
**Yiqun Zhang**, Sen Feng, Pengkai Wang, Zexi Tan, Xiaopeng Luo, Yuzhu Ji, Rong Zou and Yiu-ming Cheung<sup>&#x2709;</sup>

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
ESWA'25</span> 
[Learning Unified Distance Metric for Heterogeneous Attribute Data Clustering](https://www.sciencedirect.com/science/article/abs/pii/S0957417425003604)<br>
**Yiqun Zhang**, Mingjie Zhao, Yizhou Chen, Yang Lu<sup>&#x2709;</sup> and Yiu-ming Cheung

- <span style="display: inline-block; background-color: #0b5394; color: #ffffff; padding: 2px 8px; border-radius: 4px; font-weight: bold; font-size: 0.85em; margin-right: 10px; vertical-align: middle; line-height: 1.2;">
TPAMI'22</span> 
[Learnable Weighting of Intra-attribute Distances for Categorical Data Clustering with Nominal and Ordinal Attributes](https://ieeexplore.ieee.org/abstract/document/9346004)<br>
**Yiqun Zhang** and Yiu-ming Cheung<sup>&#x2709;</sup>

  ... ... For a full list of publications, please visit [DBLP](https://dblp.org/pid/125/5587-6.html)  &#124; [Google Scholar](https://scholar.google.com/citations?user=EnqM5F4AAAAJ&hl) ... ...

<span class='anchor' id="honors-and-awards"></span>

# 🏆 Honors & Awards
<!-- 
- *2026/02*: IEEE汇刊TETCI优秀编委
-->
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

# 👨‍🎓 Educations
- *2014/09 - 2019/11*: Ph.D. in Computer Science, Hong Kong Baptist University (Supervisor: Prof. Yiu-ming Cheung (IEEE Fellow, AAAS Fellow, and IAPR Fellow, Changjiang Chair Professor)
- *2013/09 - 2014/11*: M.Sc. in Computer Science, Hong Kong Baptist University
- *2009/09 - 2013/07*: B.Eng. in Biomedical Engineering, South China University of Technology
- *2006/09 - 2009/07*: Science Class, Shenzhen Hongling High School

<span class='anchor' id="invited-talks"></span>

# 💬 Invited Talks
- *2025/12*: Clustering Analysis of Complex Distributed Data under Dynamic Environments, Shanxi University
- *2024/12*: Clustering Complex Data Under Dynamic Environments, Northeastern University/State Key Laboratory of Synthetical Automation for Process Industries
- *2024/12*: Clustering Analysis of Complex Data under Dynamic Environments, Guangdong University of Technology
- *2023/11*: Learning from Complex Data with Cross-Coupled Heterogeneous Attributes, Southern University of Science and Technology (SUSTech)
- *2021/04*: Insights into AI Research: A Dual Perspective from Authors and Reviewers, Guangdong University of Technology
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
-



