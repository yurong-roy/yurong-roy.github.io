---
layout: about
title: Me
permalink: /
subtitle: 

profile:
  align: right
  image: prof_pic_compress.jpg
  image_circular: false # crops the image to make it circular
  #more_info: >
  #  <p>555 your office number</p>
  #  <p>123 your address street</p>
  #  <p>Your City, State 12345</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
# selected_papers: false # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
Hi! I am currently the head of Language And Science AI Lab (LASA) of [DAMO Academy of Alibaba Group](https://damo.alibaba.com/). I am generally interested in developing the novel and efficient models with various complex data structures, includeing graphs and sequences to tackle real-world challenges, particularly in the realm of Language and Science.

Prior joining DAMO Academy, I served as a principal researcher at [Tencent AI Lab](https://ai.tencent.com/) for seven years. I briefly served as a Postdoctoral Research Fellow at The Chinese University of Hong Kong. I received Ph.D degree at [The Chinese University of Hong Kong](https://www.cuhk.edu.hk/) in 2016, under the supervision of Professor [Hong CHENG](https://www1.se.cuhk.edu.hk/~hcheng/). Before that I obtained my B.S. degree with honors from [Sun Yat-sen University](https://www.sysu.edu.cn/).



<h2 class="publications"><a href="{{ '/news/' | relative_url }}" style="color: inherit;">🔥 What's New </a></h2>
<div class="news">
{%- include news.html limit=true %}
</div>

<h2 class="publications">🔍 Current Research Topics</h2>
- Deep Graph Learning
   - Foundations of Graph Neural Network
- Large Language Models
- AI for Science
   - AI for Drug Discovery
   - Physical Dynamic Simulation



## 📝 Recent Publications
<div class="publications">
{% bibliography -f {{ site.scholar.bibliography }} -q @*[selected=true && year>=2023]* %}
</div>

<!-- ## 💬 Talks -->
<h2 id="talks" class="publications">💬 Talks</h2>

<h2 id="honors-and-awards" class="publications">🎖Honors and Awards</h2>
 - **2022**, Champion of 2nd Open Catalyst Challenge, NeurIPS
 - **2020**, 10% of High-scoring Reviewers, NeurIPS
 - **2017**, Research Fellowship Scheme, CUHK
 - **2012**, Outstanding Undergraduate Thesis Award, SYSU
 - **2012**, National Undergraduate Scholarship, MoE
 - **2011**, Google Excellence Scholarship, Google
