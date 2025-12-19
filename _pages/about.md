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

I'm a second-year master student majored in Computer Science at Shanghai Jiao Tong University, under the supervision of Prof. [Chihao Zhang](http://chihaozhang.com/). 
My research interest mainly includes online learning for decision making, particularly multi-armed bandits (mab) with its variants, such as combinatorial mab, linear contextual bandits and mab in the streaming model. Furthermore, I read a series of theoretical works about online learning including RL theory and machine learning theory and develop a decent foundation. From the course "Topics in Modern Algorithms" offered by my instructor, I also have learnt some basic knowledge about high-dimensional probability and stochastic differential equation. I'm always eager to explore new areas and get fully prepared to embrace fresh challenges. 

I also have a plan to seek Ph.D. opportunities for Fall 2027. Please feel free to reach out if you think my background aligns with your research!
<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 🏫 Educations
<!--
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2020.09 - 2024.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->
**Shanghai Jiao Tong University**
<p style="text-align:left;"><i>B.Eng. in Computer Science and Engineering</i><span style="float:right;"><i>September 2020 - June 2024</i></span></p>

* GPA 90.77/100 (or 3.90/4.3), Rank 10/105
* CET6: 604 <i>(December 2021)</i>

**Shanghai Jiao Tong University** 
<p style="text-align:left;"><i>MA.Eng. in Computer Science and Engineering</i><span style="float:right;"><i>September 2024 - March 2027 (Expected)</i></span></p>

* GPA 3.87/4.0

<!-- # 🔥 News
- *May 2025*: 🍾🍾 Our work is accepted by **COCOON 2025**.  -->

# 📝 Publications 
<!--
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**
-->
* <p> Understanding Memory-Regret Trade-Off for Streaming Stochastic Multi-Armed Bandits. <br>
    Yuchen He, <b>Zichun Ye</b>, Chihao Zhang. <br>
    In Proceedings of the ACM-SIAM Symposium on Discrete Algorithms (<b>SODA 2025</b>).</p>
  
* <p> Tight Gap-Dependent Memory-Regret Trade-Off for Single-Pass Streaming Stochastic Multi-Armed Bandits. <br>
    <b>Zichun Ye</b>, Chihao Zhang, Jiahao Zhao. <br>
    In International Computing and Combinatorics Conference (<b>COCOON 2025</b>).</p> 
    
* <p> Near-Optimal Regret for Efficient Stochastic Combinatorial Semi-Bandits. <br>
    <b>Zichun Ye</b>, Runqi Wang, Xutong Liu, Shuai Li. <br>
    In submission.</p>
<!--     <b>Zichun Ye</b>, Runqi Wang, Xutong Liu, Shuai Li. <br> -->
    

# 👨‍🔬 Experiences
-- **Research Experience**
* <p style = "text-align:left;"> Memory-Regret Trade-Off for Streaming Stochastic Multi-Armed Bandits <span style="float:right;"> <i>May 2023 – March 2025</i> </span> <br> 
    Advisor: Prof. Chihao Zhang, SJTU.</p>

* <p style = "text-align:left;"> Near-Optimal Regret for Efficient Stochastic Combinatorial Semi-Bandits <span style="float:right;"> <i>March 2025 – August 2025</i> </span> <br> 
    Advisor: Prof. Xutong Liu, UW, Tacoma, Prof. Shuai Li, SJTU.</p>

* <p style = "text-align:left;"> Unlearning for Offline Stochastic Multi-Armed Bandits <span style="float:right;"> <i>October 2025 – Present</i> </span> <br> 
    Advisor: Prof. Xutong Liu, UW, Tacoma, Prof. Mengfan Xu, UMass, Prof. Mohammad Hajiesmaili, UMass.</p>

-- **Teaching Assistant**
* <p style = "text-align:left;"> CS3958: Topics in Modern Algorithms, <span style="float:right;"> <i>Fall 2023</i> </span> <br>
  with Houshuang Chen, instructed by Chihao Zhang.</p>
  
* <p style = "text-align:left;"> CS3936: Topics in Modern Algorithms, <span style="float:right;"> <i>Fall 2024</i> </span> <br>
  instructed by Chihao Zhang.</p>

# 💻 Skills
* Programming Languages: C++, Python, LaTex.
* Technical Skills: Qt(software), MySQL(database).


# 🎖 Honors and Awards
* <p style="text-align:left;">Bosch Scholarship <span style="float:right;"> <i>December 2025</i></span></p>
* <p style="text-align:left;">Zhiyuan Honor Scholarship (Top 10%)<span style="float:right;"> <i>December 2021,2022,2023</i></span></p>
* <p style="text-align:left;">Huawei Scholarship <span style="float:right;"><i>October 2022</i> </span></p>
* <p style="text-align:left;">COSCO First Class Scholarship <span style="float:right;"><i>October 2021</i> </span></p>

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
