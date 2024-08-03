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

I'm a 3rd-year undergraduate student majoring in Information and Computing Science at **Beijing Jiaotong University**. Now I am working as a research intern at **Microsoft** under the guidance of Principal Researcher <a href="https://www.microsoft.com/en-us/research/people/juding/">Justin Ding</a>.
 Previously, I was working with NLP Group at **Peking University** under the supervision of <a href="https://wanxiaojun.github.io/">Prof. Xiaojun Wan</a>.

As a student with a multidisciplinary background in Mathematics and Artificial Intelligence, strong foundations in research and leadership roles, I am keen on exploring opportunities that can deepen my understanding of Generative AI.

<a href="https://1drv.ms/b/s!AoP3c6HrNVOLgacCzg33i-YQDyD6mA?e=qgjgtD">My CV</a>

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
-*2024.08*: &nbsp;🎉🎉 I will join Microsoft as Researcher Intern in August under the guidance of Principal Researcher <a href="https://www.microsoft.com/en-us/research/people/juding/">Justin Ding</a>.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Manuscripts submitted to EMNLP 2024</div><img src='images/Example_page-0001.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DSGram: Dynamic Weighting Sub-Metrics for Grammartical Error Correction in the Era of Large Language Models](https://1drv.ms/b/s!AoP3c6HrNVOLgaY0NkVPDlKkig_m1A?e=T3Qiax)

**Jinxiang Xie**, Yilin Li, Xunjian Yin, Xiaojun Wan

[**Project**](https://github.com/jxtse/GEC_Metrics_LLM) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> | <a href="https://1drv.ms/b/s!AoP3c6HrNVOLgaY0NkVPDlKkig_m1A?e=H3dw3y">Link to paper</a>
- Proposed a novel dynamic weighting evaluation method using automated analytic hierarchy process.
- Integrated LLMs to simulate human scoring to make models closer to human feedback, labeled a dataset with more than
1,000 scoring.
- Verified the consistency of the dataset with human feedback, and fine-tuned a low-cost lightweight model.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2024.05* Honorable Mention of 2024 Mathematical Contest In Modeling 
- *2023.04* First Prize of 2023 Beijing Jiaotong University Mathematical Modeling Competition

# 📖 Educations
- *2021.09 - 2025.06*, Bachelor of Science in Information and Computing Science, Beijing Jiaotong University.
- *2025.09 - 2028.06*(expected), Master of Science in Kuang Yaming Honors School, Nanjing University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- Summer Workshop Student, *2023.05 - 2023.07*, School of Computer, National University of Singapore, Singapore.
(Supervisor: <a href="https://www.comp.nus.edu.sg/cs/people/ctank/"> Prof. Colin Tan</a> and<a href="https://www.comp.nus.edu.sg/cs/people/boyd/"> Prof. Boyd Anderson</a> )
- Research Intern, *2023.11 - 2024.07*, Wangxuan Institute of Computer Technology, Peking University, Beijing, China. 
(Supervisor: <a href="https://wanxiaojun.github.io/">Prof. Xiaojun Wan</a>)
- Research Intern, *2024.08 - Present*, DKI Group, Microsoft, Beijing, China. 
(Supervisor: Principal Researcher <a href="https://www.microsoft.com/en-us/research/people/juding/">Justin Ding</a>)

# 📚 Blogs

<div class='paper-box'><div class='paper-box-image'><div><img src='images/pic02.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LLMs: Cutting-Edge Technology and Future Applications](https://mp.weixin.qq.com/s?__biz=Mzg5NzczMzM3MA==&mid=2247483926&idx=1&sn=c6dcaf93ec8d7ecaa760df4682589b21)

My notes from a presentation on LLMs at the Gaoling Schoolof Artificial Intelligence, Renmin University of China, which featured people from top research institutions.

[Prompt Engineering: How To Ask LLMS Better](https://sspai.com/post/82322)

Introduce a number of methods for optimizing the output of large language models and reducing the probability of irrelevant or incorrect responses.
</div>