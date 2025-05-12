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
# 👤 About me
I am a Ph.D. student at the Institute for Artificial Intelligence, Peking University. I am working under the supervision of Prof. Yaodong Yang, my first initiation mentor in multi-agent systems. My research interests include reinforcement learning, game theory, and their intersection with fundamental science. The current topics I am focused on are:
- **Multi-agent Learning**: Developing practical algorithms for large-scale system control and multi-player computer games.
- **Reinforcement Learning for Science**: Exploring the potential of reinforcement learning in fundamental scientific problems.



# 🔥 News
- **_2025.05_**: &nbsp;🎉🎉 One paper gets accepted in **_ICML 2025_**.
- **_2025.01_**: &nbsp;🎉🎉 Two papers get accepted in **_ICLR 2025_**.
- **_2024.12_**: &nbsp;🎉🎉 One paper gets accepted in **_AAMAS 2025_**.
- **_2024.12_**: &nbsp;🎉🎉 One paper gets accepted in **_AAAI 2025_**.
- **_2024.09_**: &nbsp;🎉🎉 One paper gets accepted in **_NeurIPS 2024_**.
- **_2024.07_**: &nbsp;🎉🎉 One paper gets accepted on **_Nature Machine Intelligence_**.



# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Nature Machine Intelligence</div><img src='images/NMI_fig.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Efficient and Scalable Reinforcement Learning for Large-scale Network Control](https://www.nature.com/articles/s42256-024-00879-7)

**Chengdong Ma\***, Aming Li\*, Yali Du\*, Hao Dong, Yaodong Yang  <be>

This work has been covered by: <br>
[新华网 XinHua Net](http://www.news.cn/tech/20240904/1eeb042bdd5f4c6187fe0e2aa31196db/c.html)<br>
[科技日报 Science and Technology Daily](https://app.kjrb.com.cn/app/template/displayTemplate/news/newsDetail/136908.html?isDigital=true&isShare=true)<br>
[北京大学新闻网 Peking University News](https://news.pku.edu.cn/jxky/8d095ff4be784b7c9431125fe5658e45.htm)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/MPO.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Magnetic Preference Optimization: Achieving Last-iterate Convergence for Language Model Alignment](https://arxiv.org/abs/2410.16714)

Mingzhi Wang, **Chengdong Ma**, Qizhi Chen, Linjian Meng, Yang Han, Jiancong Xiao, Zhaowei Zhang, Jing Huo, Weijie J. Su, Yaodong Yang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAMAS 2025</div><img src='images/MFCIL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mean Field Correlated Imitation Learning](https://arxiv.org/abs/2997.06714)

Zhiyu Zhao, **Chengdong Ma**, Qirui Mi, Ning Yang, Xue Yan, Mengyue Yang, Haifeng Zhang, Jun Wang, Yaodong Yang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/panacea.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Panacea: Pareto Alignment via Preference Adaptation for LLMs](https://proceedings.neurips.cc/paper_files/paper/2024/hash/89f39d0b3d49a47606a165eefba2778c-Abstract-Conference.html)

Yifan Zhong\*, **Chengdong Ma\***, Xiaoyuan Zhang\*, Ziran Yang, Haojun Chen, Qingfu Zhang, Siyuan Qi, Yaodong Yang

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv 2023</div><img src='images/RTG.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Evolving Diverse Red-team Language Models in Multi-round Multi-agent Games](https://arxiv.org/abs/2310.00322)

**Chengdong Ma\***, Ziran Yang\*, Hai Ci, Jun Gao, Minquan Gao, Xuehai Pan, Yaodong Yang

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2022</div><img src='images/IROS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scalable model-based policy optimization for decentralized networked systems](https://ieeexplore.ieee.org/abstract/document/9982253)

Yali Du\*, **Chengdong Ma\***, Yuchen Liu, Runji Lin, Hao Dong, Jun Wang, Yaodong Yang
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Access</div><img src='images/car_combat.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Confrontation and Obstacle-Avoidance of Unmanned Vehicles Based on Progressive Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/10130281)

**Chengdong Ma**, Jianan Liu, Saichao He, Wenjing Hong, Jia Shi
</div>
</div>

<span class='anchor' id='-resource'></span>
# 📦 Resources and Tutorials
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025 Tutorial</div><img src='images/alignment_slides.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Alignment Methods in Large Language Models](https://icml.cc/virtual/2025/tutorial/40005)

Mingzhi Wang, **Chengdong Ma**, Yaodong Yang
</div>
</div>

<span class='anchor' id='-invited-talks'></span>
# 🎙 Talks
- **_2024.12_**: Invited Talk in Distributed Artificial Intelligence (DAI) conference.
- **_2024.10_**: Invited Talk at National Key Lab of Autonomous Intelligent Unmanned Systems in Beijing Institute of Technology.
- **_2024.09_**: Invited Talk at Cognitive Computing and Reasoning Lab in Beijing Institute for General Artificial Intelligence.



