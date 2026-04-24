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

I am a doctoral student majoring in Software Engineering at [University College London](https://www.ucl.ac.uk/), co-supervised by [Dr. He Ye](https://heye.me/) and [Prof. Federica Sarro](http://www0.cs.ucl.ac.uk/staff/F.Sarro/). I'm currently engaged in research related to deep learning and software engineering. My research interests mainly focus on fields such as computer vision, natural language processing, and the application of AI Agents.

In the past few years, I have focused on developing new deep learning algorithms to solve practical problems, particularly making progress in multi-modal generation. I believe that artificial intelligence technology can bring positive changes to society and am committed to combining theoretical research with practical applications.

My research interest includes multimodal learning, cross-domain transfer and AI for SSE. 

<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


<!-- # 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/heragent.png' alt="HerAgent" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HerAgent: Rethinking the Automated Environment Deployment via Hierarchical Test Pyramid](https://arxiv.org/pdf/2602.07871)

**Xiang Li**, Siyu Lu, Federica Sarro, Claire Le Goues, He Ye

*arXiv preprint arXiv:2602.07871, 2026.*

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ReCode 2026</div><img src='images/jmigbench-2.png' alt="JMigBench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[JMigBench: A Benchmark for Evaluating LLMs on Source Code Migration (Java 8 to Java 11)](https://doi.org/10.1145/3786180.3788316)

Nishil Amin, Zhiwei Fei, **Xiang Li**, Justyna Petke, He Ye

*1st Workshop on Code Translation, Transformation, and Modernization (ReCode 2026), co-located with ICSE 2026. ACM.*

</div>
</div>




<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ReCode 2026</div><img src='images/envintheloop_backup.png' alt="Environment-in-the-Loop" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Environment-in-the-Loop: Rethinking Code Migration with LLM-based Agents](https://doi.org/10.1145/3786180.3788315)

**Xiang Li**, Zhiwei Fei, Federica Sarro, He Ye

*1st Workshop on Code Translation, Transformation, and Modernization (ReCode 2026), co-located with ICSE 2026. ACM.*

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WACV 2025</div><img src='images/soccercomment.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MultiModal Large Language Model with RAG Strategies in Soccer Commentary Generation](https://openaccess.thecvf.com/content/WACV2025/papers/Li_Multi-Modal_Large_Language_Model_with_RAG_Strategies_in_Soccer_Commentary_WACV_2025_paper.pdf)

**Xiang Li**, Yangfan He, Shuaishuai Zu, Zhengyang Li, Tianyu Shi, Yiting Xie, Kevin Zhang

*IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2025.*

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/soccerbench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SCBench: A Sports Commentary Benchmark for Video LLMs](https://arxiv.org/pdf/2412.17637?)

Kuangzhi Ge, Lingjun Chen, Kevin Zhang, Yulin Luo, Tianyu Shi, Liaoyuan Fan, **Xiang Li**, Guanqun Wang, Shanghang Zhang

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV Workshops 2024</div><img src='images/mcre.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MCRE: Multimodal Conditional Representation and Editing for Text Motion Generation](https://dl.acm.org/doi/abs/10.1007/978-3-031-92591-7_26)

Tengjiao Sun, **Xiang Li**, Tianyu Shi, Jiahui Peng, Sheng Zheng, Hansung Kim

*European Conference on Computer Vision (ECCV) Workshops 2024: Foundation Models for 3D Humans (pp. 406–414).*

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurlPS 2024</div><img src='images/uniTMGE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uniform Text-Motion Generation and Editing via Diffusion Model.](https://openreview.net/forum?id=X078V9YU2x)

Ruoyu Wang, **Xiang Li**(Co-first author), Tengjiao Sun, Yangfan He, Tianyu Shi, Yiting Xie

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">European Journal of Agronomy</div><img src='images/MSCP-net.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Developing a Deep Learning Network MSCP-Net to Automatically and Accurately Generate Maize Stalk Anatomical Traits Related with Plant Lodging Resistance and Yield.](https://www.sciencedirect.com/science/article/abs/pii/S1161030124002466)

Haiyu Zhou, **Xiang Li**(Co-first author), Yufeng Jiang, Xiaoying Zhu, Taiming Fu, Mingchong Yang, Weidong Cheng, Xiaodong Xie, Yan Chen, Lingqiang Wang



</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<span class='anchor' id='educations-work-experience'></span>

# 📖 Educations and Work Experience
- *2025.10 - present*, University College London, Software Engineering, PhD Student 
- *2024.08 - 2025.06*, Southern University of Science and Technology, Statistics, Research Assistant. 
- *2022.07 - 2024.06*, Li Auto Inc., Algorithm Engineer. 
- *2019.09 - 2022.06*, Guangxi University, Computer Science and Technology, Master's Degree. 
- *2014.09 - 2018.06*, Zhengzhou University, Biology Engineering, Bachelor's Degree. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->
