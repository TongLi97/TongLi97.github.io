---
layout: archive
title: "Publications(Last Update: 10/07/2024)"
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

.publication-container {
    display: flex !important;
    align-items: flex-start !important;
    margin-bottom: 20px !important;
}
.publication-image {
    flex: 0 0 150px !important;
    margin-right: 20px !important;
}
.publication-image img {
    width: 150px !important;
    height: auto !important;
    border: 1px solid #ddd !important;
    border-radius: 4px !important;
}
.publication-text {
    flex: 1 !important;
}
</style>


## Publications

<div style="display: flex; align-items: flex-start; margin-bottom: 20px; width: 150px;">
    <!-- 左侧图片 -->
    <div style="flex: 0 0 20px; margin-right: 20px;">
        <img src="/images/ChinaVis.png" alt="Paper 1 Thumbnail" style="width: 150px; height: auto; border: 1px solid #ddd; border-radius: 4px;">
    </div>
    <!-- 右侧文字 -->
    <div class="hhh" style="position: relative; left: 20px; top: 20px;">
        <p style="font-weight: bold; font-size: 1.1em; margin-bottom: 5px;">Centennial Drama Reimagined: An Immersive Experience of Intangible Cultural Heritage through Contextual Storytelling in Virtual Reality</p>
        <p style="margin: 0; font-size: 0.9em;">**Jian Yu**, Zhan Wang, Yifan Cao, Hao Cui, <b>Wei Zeng*</b></p>
        <p style="margin: 0; font-size: 0.9em;"><i>ACM Journal on Computing and Cultural Heritage</i>, 2025. Accepted.</p>
        <p><a href="#" style="color: #007acc; text-decoration: none;">[Paper]</a></p>
    </div>
</div>

<div class="publication-item">
    <div class="publication-image">
        <img src="/images/ChinaVis.png" alt="Paper 2 Thumbnail">
    </div>
    <div class="publication-info">
        <p class="publication-title">AI-rays: Exploring Bias in the Gaze of AI Through a Multimodal Interactive Installation</p>
        <p class="publication-authors">**Ziyao Gao**, Yiwen Zhang, Ling Li, Theodoros Papatheodorou, <b>Wei Zeng*</b></p>
        <p class="publication-journal"><i>Proceedings of Siggraph Asia 2024 Art Paper</i>, 2025. Accepted.</p>
        <p class="publication-link">[<a href="#">Paper</a>]</p>
    </div>
</div>

<div class="publication-item">
    <div class="publication-image">
        <img src="/images/ChinaVis.png" alt="Paper 3 Thumbnail">
    </div>
    <div class="publication-info">
        <p class="publication-title">Advancing Multimodal Large Language Models in Chart Question Answering with Visualization-Referenced Instruction Tuning</p>
        <p class="publication-authors">**Xingchen Zeng**, Haichuan Lin, Yilin Ye, <b>Wei Zeng*</b></p>
        <p class="publication-journal"><i>IEEE Transactions on Visualization and Computer Graphics</i> (Proc. IEEE VIS 2024), 2025. Accepted.</p>
        <p class="publication-link">[<a href="#">Paper</a>]</p>
    </div>
</div>

<div class="publication-item">
    <div class="publication-image">
        <img src="/images/ChinaVis.png" alt="Paper 4 Thumbnail">
    </div>
    <div class="publication-info">
        <p class="publication-title">ModalChorus: Visual Probing and Alignment of Multi-modal Embeddings via Modal Fusion Map</p>
        <p class="publication-authors">**Yilin Ye**, Shishi Xiao, Xingchen Zeng, <b>Wei Zeng*</b></p>
        <p class="publication-journal"><i>IEEE Transactions on Visualization and Computer Graphics</i> (Proc. IEEE VIS 2024), 2025. Accepted.</p>
        <p class="publication-link">[<a href="#">Paper</a>]</p>
    </div>
</div>
<!-- End of each publication entry -->
