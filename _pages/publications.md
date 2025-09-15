---
title: "Publications"
permalink: /publications/
layout: single
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/CompoVis.png" alt="CompoVis Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">IEEE TMM</div>
</div>
<div style="flex: 1;">
<strong>CompoVis: Is Cross-modal Semantic Alignment of CLIP Optimal? A Visual Analysis Attempt</strong><br>
<span style="color: #2174A8;">Tong Li</span>, Guodao Sun*, Xueqian Zheng, Qi Jiang, Wang Xia, Xu Tan, Haidong Gao, Haixia Wang & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>IEEE Transactions on Multimedia (TMM)</strong>, 2025
</div>
<a href="https://huggingface.co/datasets/guodaosun/CompoVIS" style="color: #2174A8; text-decoration: none; margin-right: 15px;">[Dataset]</a>
<a href="https://github.com/TongLi97/HERCSOM-layout" style="color: #2174A8; text-decoration: none;">[Algorithm]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/AutoMA.png" alt="AutoMA Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">PacificVis</div>
</div>
<div style="flex: 1;">
<strong>AutoMA: Automated Generation of Multi-level Annotations for Time Series Visualization</strong><br>
Qi Jiang, Guodao Sun*, <span style="color: #2174A8;">Tong Li</span>, Jingwei Tang, Wang Xia, Yunchao Wang, Li Jiang & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>IEEE Pacific Visualization Symposium (PacificVis)</strong>, 2025
</div>
<a href="https://ieeexplore.ieee.org/document/11021060" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/PacificVis2025.png" alt="PacificVis2025 Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">PacificVis</div>
</div>
<div style="flex: 1;">
<strong>Probing the Compositional Understanding in VLMs with Visualization Representation and Insights</strong><br>
<span style="color: #2174A8;">Tong Li</span>, Guodao Sun*, Xueqian Zheng, Haixia Wang & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>IEEE Pacific Visualization Symposium (PacificVis)</strong>, 2025
</div>
<a href="/files/PacificVis2025_Poster_A0.pdf" style="color: #2174A8; text-decoration: none;">[Poster]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/Skelemap.jpg" alt="Skelemap Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">JoV</div>
</div>
<div style="flex: 1;">
<strong>skelemap: skeleton-based boundary growth for efficient and automated cartogram generation</strong><br>
Yunchao Wang, Guodao Sun*, Zihao Zhu, <span style="color: #2174A8;">Tong Li</span> & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>Journal of Visualization</strong>, 2024
</div>
<a href="https://link.springer.com/article/10.1007/s12650-024-01031-8" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/xia.png" alt="Video Visualization Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">IEEE TCSVT</div>
</div>
<div style="flex: 1;">
<strong>Video Visualization and Visual Analytics: A Task-Based and Application-Driven Investigation</strong><br>
Wang Xia, Guodao Sun*, <span style="color: #2174A8;">Tong Li</span>, Baofeng Chang, Jingwei Tang, Gefei Zhang & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)</strong>, 2024
</div>
<a href="/files/xia.pdf" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/Lander.png" alt="LANDER Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">IEEE THMS</div>
</div>
<div style="flex: 1;">
<strong>LANDER: Visual Analysis of Activity and Uncertainty in Surveillance Video</strong><br>
<span style="color: #2174A8;">Tong Li</span>, Guodao Sun*, Baofeng Chang, Yunchao Wang, Qi Jiang, Yuanzhong Ying, Li Jiang, Haixia Wang & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>IEEE Transactions on Human-Machine Systems (THMS)</strong>, 2024
</div>
<a href="https://ieeexplore.ieee.org/document/10570041" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/Qutaber.png" alt="Qutaber Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">ChinaVis</div>
</div>
<div style="flex: 1;">
<strong>Qutaber: Task-based Exploratory Data Analysis with Enriched Context Awareness</strong><br>
Qi Jiang, Guodao Sun*, <span style="color: #2174A8;">Tong Li</span>, Jingwei Tang, Wang Xia, Sujia Zhu & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>China Conference on Data Visualization (ChinaVis)</strong>, 2023
</div>
<a href="https://link.springer.com/article/10.1007/s12650-024-00975-1" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/Storyline.png" alt="E2Storyline Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">ACM TIST</div>
</div>
<div style="flex: 1;">
<strong>E2Storyline: Visualizing the Relationship with Triplet Entities and Event Discovery</strong><br>
Yunchao Wang, Guodao Sun*, Zihao Zhu, <span style="color: #2174A8;">Tong Li</span>, Ling Chen & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>ACM Transactions on Intelligent Systems and Technology (TIST)</strong>, 2023
</div>
<a href="/files/Storyline.pdf" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/MUSE.png" alt="MUSE Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">IEEE TVCG</div>
</div>
<div style="flex: 1;">
<strong>MUSE: Visual Analysis of Musical Semantic Sequence</strong><br>
Baofeng Chang, Guodao Sun*, <span style="color: #2174A8;">Tong Li</span>, Houchao Huang, Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>IEEE Transactions on Visualization and Computer Graphics (TVCG)</strong>, 2022
</div>
<a href="/files/MUSE.pdf" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>

---

<div style="display: flex; align-items: flex-start; margin-bottom: 30px;">
<div style="position: relative; flex-shrink: 0; margin-right: 20px;">
<img src="/images/SurVizor.png" alt="SurVizor Paper" width="250" style="border-radius: 8px;">
<div style="position: absolute; top: 8px; left: 8px; background-color: #2174A8; color: white; padding: 4px 8px; border-radius: 4px; font-size: 11px; font-weight: bold;">ChinaVis</div>
</div>
<div style="flex: 1;">
<strong>SurVizor: Visualizing and Understanding the Key Content of Surveillance Videos</strong><br>
Guodao Sun*, <span style="color: #2174A8;">Tong Li</span> & Ronghua Liang<br><br>
<div style="background-color: #E6F3FF; border-left: 4px solid #2174A8; padding: 8px 12px; border-radius: 4px; margin: 5px 0; font-size: 14px; color: #1B5A87;">
✅ <strong>China Conference on Data Visualization (ChinaVis)</strong>, 2021
</div>
<a href="/files/SurVizor.pdf" style="color: #2174A8; text-decoration: none;">[Paper]</a>
</div>
</div>



