---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

* Towards LLM-driven Dialogue State Tracking. [[PDF](https://arxiv.org/pdf/2310.14970.pdf)] [[Code](https://github.com/WoodScene/LDST)]  
  **Yujie Feng**, Zexin Lu, Bo Liu, Liming Zhan, Xiao-Ming Wu.  
  Conference on Empirical Methods in Natural Language Processing (**EMNLP 2023**).  
 
* Spatial-Attention and Demographic-Augmented Generative Adversarial Imputation Network for Population Health Data Reconstruction. [[PDF](https://ieeexplore.ieee.org/abstract/document/9976200)] [[Code](https://github.com/WoodScene/SDAGAIN)]  
  **Yujie Feng**, Jiangtao Wang, Yasha Wang, Xu Chu.  
  IEEE Transactions on Big Data (**IEEE TBD**).  

* Towards Sustainable Compressive Population Health: A GAN-based Year-By-Year Imputation Method. [[PDF](https://dl.acm.org/doi/abs/10.1145/3571159)] [[Code](https://github.com/WoodScene/UAA-GAIN)]  
  **Yujie Feng**, Jiangtao Wang, Yasha Wang, Xu Chu.  
  ACM Transactions on Computing for Healthcare.  

* Completing missing prevalence rates for multiple chronic diseases by jointly leveraging both intra-and inter-disease population health data correlations. [[PDF](https://dl.acm.org/doi/abs/10.1145/3442381.3449811)] [[Code](https://github.com/WoodScene/Compressive-Population-Health)]  
  **Yujie Feng**, Jiangtao Wang, Yasha Wang, Sumi Helal.  
  Proceedings of the Web Conference 2021 (**WWW 2021**).  

# Preprint
* How Good Are Large Language Models at Out-of-Distribution Detection?  
  Bo Liu, Liming Zhan, Zexin Lu, **Yujie Feng**, Lei Xue, Xiao-Ming Wu.  2023。
