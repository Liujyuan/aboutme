---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

* denotes co-first author and <sup>&#8224;</sup> denotes corresponding author

<img src='../paper_imgs/Agent4Rec.png' style='float:left;width:280px;height:160px;margin-left:20px;margin-right:20px'/>
**On Generative Agents in Recommendation**  
An Zhang\*, **Leheng Sheng\***, Yuxin Chen\*, Hao Li, Yang Deng, Xiang Wang<sup>&#8224;</sup>, Tat-Seng Chua

**Arxiv, 2023.10** [[Paper](https://arxiv.org/pdf/2310.10108.pdf)] [[Arxiv](https://arxiv.org/abs/2310.10108)] [[Code](https://github.com/LehengTHU/Agent4Rec)]  


<img src='../paper_imgs/AdvInfoNCE.png' style='float:left;width:280px;height:160px;margin-left:20px;margin-right:20px'/>
**Empowering Collaborative Filtering with Principled Adversarial Contrastive Loss**  
An Zhang\*, **Leheng Sheng\***, Zhibo Cai<sup>&#8224;</sup>, Xiang Wang, Tat-Seng Chua  

**NeurIPS, 2023** [[Paper](https://neurips.cc/virtual/2023/poster/71149)] [[Code](https://github.com/LehengTHU/AdvInfoNCE)]  

<img src='../paper_imgs/BrainNetFormer.png' style='float:left;width:280px;height:160px;margin-left:20px;margin-right:20px'/>
**BrainNetFormer: Decoding Brain Cognitive States with Spatial-Temporal Cross Attention**  
**Leheng Sheng**, Wehan Wang, Zhiyi Shi, Jichao Zhan, Youyong Kong<sup>&#8224;</sup>  

**ICASSP, 2023** [[Paper](https://ieeexplore.ieee.org/abstract/document/10094655)] 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
