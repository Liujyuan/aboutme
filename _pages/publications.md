---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

\* denotes co-first author and <sup>&#8224;</sup> denotes corresponding author

<div style="display: flex; flex-direction: column;">

  <!-- 第一组图片和段落 -->
  <div style="display: flex; align-items: flex-start;">
    <!-- 图片部分（1/3） -->
    <div style="flex: 1;">
      <img src="../paper_imgs/agent4rec.png" style="width: 100%; height: auto;">
    </div>
    <!-- 文字部分（2/3） -->
    <div style="flex: 2; padding-left: 20px;">
      <p style="margin-bottom: 50px;"><strong>On Generative Agents in Recommendation</strong><br>
      An Zhang*, <strong>Leheng Sheng*</strong>, Yuxin Chen*, Hao Li, Yang Deng, Xiang Wang†, Tat-Seng Chua<br>
      <strong>Arxiv, 2023.10</strong><br>
    <a href="https://arxiv.org/pdf/2310.10108.pdf">[Paper]</a> <a href="https://arxiv.org/abs/2310.10108">[Arxiv]</a> <a href="https://github.com/LehengTHU/Agent4Rec">[Code]</a>
      </p>
    </div>
  </div>
  <!-- 第二组图片和段落 -->
  <div style="display: flex; align-items: flex-start;">
    <!-- 图片部分（1/3） -->
    <div style="flex: 1;">
      <img src="../paper_imgs/AdvInfoNCE.png" style="width: 100%; height: auto;">
    </div>
    <!-- 文字部分（2/3） -->
    <div style="flex: 2; padding-left: 20px;">
      <p style="margin-bottom: 50px;"><strong>Empowering Collaborative Filtering with Principled Adversarial Contrastive Loss</strong><br>
      An Zhang*, <strong>Leheng Sheng*</strong>, Zhibo Cai†, Xiang Wang, Tat-Seng Chua<br>
    <strong>NeurIPS, 2023 (CCF A)</strong><br>
    <a href="https://neurips.cc/virtual/2023/poster/71149">[Paper]</a> <a href="https://arxiv.org/abs/2310.18700">[Arxiv]</a> <a href="https://github.com/LehengTHU/AdvInfoNCE">[Code]</a>
      </p>
    </div>
  </div>
  <!-- 第三组图片和段落 -->
  <div style="display: flex; align-items: flex-start;">
    <!-- 图片部分（1/3） -->
    <div style="flex: 1;">
      <img src="../paper_imgs/BrainNetFormer.png" style="width: 100%; height: auto;">
    </div>
    <!-- 文字部分（2/3） -->
    <div style="flex: 2; padding-left: 20px;">
      <p style="margin-bottom: 50px;"><strong>BrainNetFormer: Decoding Brain Cognitive States with Spatial-Temporal Cross Attention</strong><br>
      <strong>Leheng Sheng</strong>, Wehan Wang, Zhiyi Shi, Jichao Zhan, Youyong Kong†<br>
    <strong>ICASSP, 2023 (CCF B)</strong><br>
    <a href="https://ieeexplore.ieee.org/abstract/document/10094655">[Paper]</a>
    </p>
    </div>
  </div>

</div>





<!-- <div style="display: flex; flex-direction: row;">
  <div style="flex: 1;">
    <img src="../paper_imgs/agent4rec.png"  style="width: 100%; height: auto;">
    <img src="../paper_imgs/AdvInfoNCE.png"  style="width: 100%; height: auto;">
    <img src="../paper_imgs/BrainNetFormer.png"  style="width: 100%; height: auto;">
  </div>
  <div style="flex: 2; padding-left: 20px;">
    <p style="margin-bottom: 50px;"><strong>On Generative Agents in Recommendation</strong><br>
    An Zhang*, <strong>Leheng Sheng*</strong>, Yuxin Chen*, Hao Li, Yang Deng, Xiang Wang†, Tat-Seng Chua<br>
    <strong>Arxiv, 2023.10</strong><br>
    <a href="https://arxiv.org/pdf/2310.10108.pdf">[Paper]</a> <a href="https://arxiv.org/abs/2310.10108">[Arxiv]</a> <a href="https://github.com/LehengTHU/Agent4Rec">[Code]</a></p>
    <p style="margin-bottom: 50px;"><strong>Empowering Collaborative Filtering with Principled Adversarial Contrastive Loss</strong><br>
    An Zhang*, <strong>Leheng Sheng*</strong>, Zhibo Cai†, Xiang Wang, Tat-Seng Chua<br>
    <strong>NeurIPS, 2023 (CCF A)</strong><br>
    <a href="https://neurips.cc/virtual/2023/poster/71149">[Paper]</a> <a href="https://github.com/LehengTHU/AdvInfoNCE">[Code]</a></p>
    <p style="margin-bottom: 50px;"><strong>BrainNetFormer: Decoding Brain Cognitive States with Spatial-Temporal Cross Attention</strong><br>
    <strong>Leheng Sheng</strong>, Wehan Wang, Zhiyi Shi, Jichao Zhan, Youyong Kong†<br>
    <strong>ICASSP, 2023 (CCF B)</strong><br>
    <a href="https://ieeexplore.ieee.org/abstract/document/10094655">[Paper]</a></p>

  </div>
</div> -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
