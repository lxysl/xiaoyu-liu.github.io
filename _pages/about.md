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

# 😉 About Me

I am a Master’s student at [Huazhong University of Science and Technology](https://hust.edu.cn), supervised by Prof. [Ye Yuan](https://yy311.github.io/).

Previously, I got my B.Eng degrees (Outstanding Graduates) from [Central South University](https://en.csu.edu.cn/).

My academic research interest includes multi-modal learning, large language model, weakly-supervised learning and vision language pre-training.

My resume can be viewed at [Here](resume.pdf).

<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv Preprint</div><img src='images/plremix.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**PLReMix: Combating Noisy Labels with Pseudo-Label Relaxed Contrastive Representation Learning** [[PDF]](https://arxiv.org/abs/2402.17589) [[GitHub]](https://github.com/lxysl/PLReMix)

**Xiaoyu Liu**, Beitong Zhou, Cheng Cheng

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TII 2023</div><img src='images/inlssl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Intelligent fault diagnosis with noisy labels via semi-supervised learning on industrial time series** [[PDF]](https://ieeexplore.ieee.org/document/10028769/)

Cheng Cheng, **Xiaoyu Liu**, Beitong Zhou, Ye Yuan

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCSVT 2024</div><img src='images/gtinet.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**GTINet: Global Topology-aware Interactions for Unsupervised Point Cloud Registration** [[PDF]](https://ieeexplore.ieee.org/document/10440120)

Yinuo Jiang, Beitong Zhou, **Xiaoyu Liu**, Qingyi Li, Cheng Cheng

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PHM 2024</div><img src='images/tc4dt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Surface roughness prediction in boring of TC4-DT with multi-sensor data and machining parameters** [Accepted]

Longjianjie Zhang, **Xiaoyu Liu**, Ziheng Zhou, Zhihui Wang, Feng Hua, Cheng Cheng

</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<span class='anchor' id='internships'></span>

<!-- Internship -->

# 💼 Internships

<p style="text-align:left;"><b><ins>Baidu, Inc.</ins></b><span style="float:right;">Jan. 2024 - Now</span></p>

*Large Language Model Algorithm Intern*

* Responsible for the content production pipeline of Baidu Zhidao, collecting relevant materials from the entire internet based on user query data, fine-tuning LLMs to generate answers, and deploying a low-cost content production line with a daily output of hundreds of thousands.

* Develop a multimodal agent routing-based response generation scheme to tackle issues arising from crucial information concealed in images. This enables the model to autonomously choose a response generation scheme based on plain text/+OCR/+original images according to the amount of information and relevance, achieving a 29\% improvement in content usability.

<span class='anchor' id='projects'></span>

<!-- Projects -->

# 💡 Projects

<p style="text-align:left;"><b><ins>Blade Knife Automatic Selection with LLM</ins></b><span style="float:right;">Jan. 2024 - Now</span></p>

*Project Leader*

* In the process of aero-engine blade machining, use CatBoost to predict a reasonable initial value of the knife size, then use LLM to automate the tool screening process until it passes the system simulation test, avoiding the tedious steps of manual trial and error.

* Design and develop a natural language interactive agent-based machining process control system, which operates serialized process objects through an LLM and realizes the fine adjustment of process flow and parameters.

* Cooperate with [JITRI - Jiangsu Industrial Technology Research Institute](https://cn.linkedin.com/company/jitri).

<p style="text-align:left;"><b><ins>LLM Agent Anime Characters Chatbot</ins></b><span style="float:right;">Nov. 2023 - Dec. 2023</span></p>

*Independent Developer*

* Build an LLM chatbot based on ModelScope, LangChain and Gradio, use prompts and document retrieval to give characters different personalities and memories. [Demo](https://www.modelscope.cn/studios/lxy7641/genshin/summary)

* Won the best popularity award in Tongyi Qianwen Agent Builder Creative Challenge Track. (20/654)

<p style="text-align:left;"><b><ins>Intelligent Anti-epidemic Disinfection Vehicle</ins></b><span style="float:right;">Sep. 2020 - May 2021</span></p>

*Project Leader*

* Develop an SSD-based mask-wearing detection algorithm for the anti-epidemic disinfection vehicle, which is deployed on Raspberry Pi 4b, with recognition accuracy reaching 89% and the speed up to 5 f/s.

* Develop the website backend based on Flask, which controls and monitors the vehicle through MQTT and RTMP.

* Collect one first-class national prize and two third-class national prizes.

<p style="text-align:left;"><b><ins>MIT-BIH ECG Arrhythmia Diagnosis</ins></b><span style="float:right;">Mar. 2020 - June 2022</span></p>

*Project Leader*

* Propose an ECG arrhythmia diagnosis algorithm based on time-series Transformer auto-encoder and GWO-SVM Optimizer.

* Develop a knowledge graph-based consultation system for cardiovascular diseases with Scrapy crawling the data and Neo4j building the graph database. [Code](https://github.com/lxysl/knowledge_graph)

* Be selected as the excellent project in the National Undergraduate Innovation and Entrepreneurship Project by Central South University. (10%)

<span class='anchor' id='educations'></span>

# 📖 Educations

<p style="text-align:left;">Huazhong University of Science and Technology<span style="float:right;">Sep. 2022 - June 2025 (expected)</span></p>

- <p>M.Sc. in Control Science and Engineering<span style="float:right;">Grade: 91.35 / 100</span></p>

<p style="text-align:left;">Central South University<span style="float:right;">Sep. 2018 - June 2022</span></p>

- <p>B.E. in Intelligent Science and Technology<span style="float:right;">Grade: 90.91 / 100</span></p>

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards

<p style="text-align:left;"><b>First-class Scholarship for Postgraduates</b> - Huazhong University of Science and Technology<span style="float:right;">2022</span></p>

<p style="text-align:left;"><b>Outstanding Graduates</b> - Central South University<span style="float:right;">2022</span></p>

<p style="text-align:left;"><b>Excellent Student</b> (10%) - Central South University<span style="float:right;">2019/2020/2021</span></p>

<p style="text-align:left;"><b>First-class National Prize</b> (Top-5 in China) - National College Student Software Innovation Competition<span style="float:right;">2020</span></p>

<p style="text-align:left;"><b>Third-class National Prize</b> (15% in China) - China Robotics and Artificial Intelligence Competition<span style="float:right;">2020</span></p>

<p style="text-align:left;"><b>Third-class National Prize</b> (20% in China) - Undergraduate Electronic Design Contest - 2020 Embedded System Design Invitational Contest<span style="float:right;">2020</span></p>

<p style="text-align:left;"><b>Third-class National Prize</b> (Top-20 in China) - Chinese Collegiate Computing Competition<span style="float:right;">2021</span></p>

<span class='anchor' id='open-source'></span>

# 💻 Open Source

* Bug Fix in [Spijkervet/SimCLR](https://github.com/Spijkervet/SimCLR/pull/46): Fix the bug in Distributed Data Parallel implementation of Pytorch SimCLR.

* [ECG Classification Baseline](https://github.com/lxysl/mit-bih_ecg_recognition): Build baseline and tutorial for MIT-BIH ECG classification and earn 100+ stars.

<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->