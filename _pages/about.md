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


I am a CS Ph.D. student at UNC Chapel Hill, supervised by [Prof. Mingyu Ding](https://dingmyu.github.io/) and [Prof. Huaxiu Yao](https://www.huaxiuyao.io/). I received both my Bachelor's and Master's degrees from Tongji University. I interned at [UC Berkeley](https://www.berkeley.edu/) as a visiting student researcher, where I collaborated with [Prof. Masayoshi Tomizuka](https://me.berkeley.edu/people/masayoshi-tomizuka/), [Prof. Mingyu Ding](https://dingmyu.github.io/),  and [Dr. Wei Zhan](https://zhanwei.site/).

My research interests include  LLM/VLM, RL , and embodied AI. And my research goal is to improve the performance of LLMs and VLMs through reinforcement learning and other post-training techniques, and to leverage these models to build efficient and intelligent agents capable of interacting with the physical world (embodied intelligence) and driving scientific exploration (AI for Science).

Besides, I am deeply interested in modeling and analyzing LLM reasoning from a geometric and dynamical systems perspective. Recently, I have been actively exploring how post-training signals, such as RL, reshape the geometry, stability of these reasoning dynamics. If you are interested in related questions, I am always happy to connect and exchange ideas.


# 🔥 News
<div class="news-container" markdown="1">
- *2026.01*: &nbsp; [SimpleMem](https://arxiv.org/abs/2601.02553) is released. [Paper](https://arxiv.org/abs/2601.02553), [Website](https://aiming-lab.github.io/SimpleMem-Page/), [Github](https://github.com/aiming-lab/SimpleMem)
- *2025.11*: &nbsp; [Agent0](https://arxiv.org/abs/2511.16043), [Agent0-VL](https://arxiv.org/abs/2511.19900) are released.
- *2025.11*: &nbsp;🎉🎉 One paper is accepted by AAAI 2026.
- *2025.10*: &nbsp; [Alignment Tipping Process: How Self-Evolution Pushes LLM Agents Off the Rails](https://arxiv.org/abs/2510.04860) is preprinted.
- *2025.09*: &nbsp; We released [SciReasoner](https://arxiv.org/abs/2509.21320), a scientific reasoning foundation model covering 103 tasks. It is pretrained on a 206B-token corpus and further enhanced through supervised fine-tuning and reinforcement learning to continually improve its reasoning ability. The model achieves state-of-the-art performance on more than 50 tasks. [Paper](https://arxiv.org/pdf/2509.21320), [Github](https://github.com/open-sciencelab/SciReason), [Hugging Face](https://huggingface.co/SciReason)
- *2025.08*: &nbsp; We released [A Survey of Scientific Large Language Models: From Data Foundations to Agent Frontiers](https://arxiv.org/abs/2508.21148), providing a comprehensive, data-centric roadmap of Sci-LLMs from foundational models to agentic frontiers. [Paper](https://arxiv.org/abs/2508.21148), [Github](https://github.com/open-sciencelab/Awesome-Scientific-Datasets-and-LLMs)
- *2025.08*: &nbsp; We released [VIPER-R1](https://arxiv.org/abs/2508.17380), a multimodal model for Visual Induction for Physics-based Equation Reasoning to discover fundamental symbolic formulas. [Paper](https://arxiv.org/pdf/2508.17380), [Project](https://jiaaqiliu.github.io/VIPER-R1/).
- *2025.06*: &nbsp; [PhysUniBench](https://arxiv.org/abs/2506.17667) is released, which is a large-scale multimodal benchmark for evaluating undergraduate-level physics reasoning in AI models. [Paper](https://arxiv.org/abs/2506.17667), [Project](https://prismax-team.github.io/PhysUniBenchmark/).
- *2025.06*: &nbsp;🎉🎉 I received my Master degree from Tongji University, and got the honor of Shanghai Outstanding Graduate(Top 1%)!
- *2025.03*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10933798) is accepted by IEEE Transactions on Vehicular Technology.
- *2025.02*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10924758) (first author) is accepted by IEEE Robotics and Automation Letters (RA-L).
- *2024.11*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10774177) (first author) is accepted by IEEE Transactions on Intelligent Transportation Systems.
- *2024.11*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10752915) (first author) is accepted by IEEE Transactions on Artificial Intelligence.
- *2024.10*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10737434) (first author) is accepted by IEEE Transactions on Intelligent Vehicles.
- *2024.08*: &nbsp;🎉🎉 [One paper](https://arxiv.org/abs/2408.06656) (Co-first author) is accepted by ECCV 2024(Oral)
- *2024.07*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10919632) (first author) is accepted by ITSC 2024.
- *2024.06*: &nbsp;🎉🎉 [One paper](http://dx.doi.org/10.1080/21680566.2024.2380913) (first author) is accepted by Transportmetrica B: Transport Dynamics.
- *2024.04*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10494558) (first author) is accepted by IEEE Transactions on Vehicular Technology.
- *2023.11*: &nbsp;🎉🎉 [One paper](https://ieeexplore.ieee.org/document/10315232) (first author) is accepted by IEEE Transactions on Intelligent Vehicles.
- *2023.07*: &nbsp;🎉🎉 Three papers were accepted by ITSC 2023
- *2022.09*: &nbsp;🎉🎉 I was bestowed with the Nominee Award for Shanghai University Student Annual Character, a recognition of paramount importance in evaluating the comprehensive aptitudes and societal influence of college students within the Shanghai municipality. Only 20 people in Shanghai receive the award each year (including nominees)!
- *2022.06*: &nbsp;🎉🎉 I received my Bachelor degree from Tongji University with the first overall ranking in my major (1/163), and I got the honor of Shanghai Outstanding Graduate(Top 1%)!
- *2021.05*: &nbsp;🎉🎉 I received the Tongji University Pursuit of Excellence Award, the highest honor for undergraduates at Tongji University! Only three undergraduates are able to receive this honor each year!
- *2020.10*: &nbsp;🎉🎉 I won the Best Paper Award in CUMCM! CUMCM is the largest basic academic competition for undergraduate students in China, and 3 papers were awarded from 42,000+ candidates!
</div>




# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Fig_overall_VIPER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mimicking the Physicist's Eye:A VLM-centric Approach for Physics Formula Discovery (VIPER-R1)](https://arxiv.org/abs/2508.17380)

**Jiaqi Liu**,  Songning Lai, Pengze Li, Di Yu, Wenjie Zhou, Yiyang Zhou, Peng Xia, Zijun Wang, Xi Chen, Shixiang Tang, Lei Bai, Wanli Ouyang, Mingyu Ding, Huaxiu Yao, Aoran Wang, accepted by NeurIPS 2025 Efficient Reasoning Workshop.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Agent0-vl.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agent0-VL: Exploring Self-Evolving Agent for Tool-Integrated Vision-Language Reasoning](https://arxiv.org/abs/2511.19900)

**Jiaqi Liu**, Kaiwen Xiong, Peng Xia, Yiyang Zhou, Haonian Ji, Lu Feng, Siwei Han, Mingyu Ding, Huaxiu Yao, arxiv:2511.19900.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/simplemem.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SimpleMem: Efficient Lifelong Memory for LLM Agents](https://arxiv.org/abs/2601.02553)

**Jiaqi Liu**$^\star$, Yaofeng Su$^\star$, Peng Xia, Siwei Han, Zeyu Zheng, Cihang Xie, Mingyu Ding, Huaxiu Yao, arxiv:2601.02553.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/Agent0.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning](https://arxiv.org/abs/2511.16043)

Peng Xia, Kaide Zeng, **Jiaqi Liu**, Can Qin, Fang Wu, Yiyang Zhou, Caiming Xiong, Huaxiu Yao, arxiv:2511.16043.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/MoA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mixture of Horizons in Action Chunking](https://arxiv.org/abs/2511.19433)

Dong Jing, Gang Wang, **Jiaqi Liu**, Weiliang Tang, Zelong Sun, Yunchao Yao, Zhenyu Wei, Yunhui Liu, Zhiwu Lu, Mingyu Ding, arxiv:2511.19433.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/ARCHE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ARCHE: A Novel Task to Evaluate LLMs on Latent Reasoning Chain Extraction](https://arxiv.org/abs/2511.12485)

Pengze Li, **Jiaqi Liu**, Junchi Yu, Lihao Liu, Mingyu Ding, Wanli Ouyang, Shixiang Tang, Xi Chen, AAAI 2026.

</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><img src='images/Sci_Reasoner.png' alt="Sci-LLM Survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SciReasoner: Laying the Scientific Reasoning Ground Across Disciplines](https://arxiv.org/abs/2509.21320)

Yizhou Wang$^\star$, Chen Tang$^\star$, Han Deng$^\star$, Jiabei Xiao$^\star$, **Jiaqi Liu**$^\star$, Jianyu Wu$^\star$, ..., Philip Torr, Shixiang Tang, Xinzhu Ma, Wanli Ouyang, Lei Bai *et al.* . arXiv:2509.21320.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/fig_atp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Alignment Tipping Process: How Self-Evolution Pushes LLM Agents Off the Rails](https://arxiv.org/abs/2510.04860)

Siwei Han, **Jiaqi Liu**, Yaofeng Su, Wenbo Duan, Xinyuan Liu, Cihang Xie, Mohit Bansal, Mingyu Ding, Linjun Zhang, Huaxiu Yao, arxiv:2510.04860.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/LLM_survey.png' alt="Sci-LLM Survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey of Scientific Large Language Models: From Data Foundations to Agent Frontiers](https://arxiv.org/abs/2508.21148)

Ming Hu, Chenglong Ma, Wei Li, Wanghan Xu, Jiamin Wu, Jucheng Hu, Tianbin Li, Guohang Zhuang, **Jiaqi Liu**, Yingzhou Lu, ..., Wanli Ouyang, Yu Qiao, Zongyuan Ge, Shixiang Tang, Junjun He *et al.* . arxiv:2508.21148.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/LDPD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Language-Driven Policy Distillation for Cooperative Driving in Multi-Agent Reinforcement Learning](https://ieeexplore.ieee.org/document/10924758)

**Jiaqi Liu**, Chengkai Xu, Peng Hang, Jian Sun, Mingyu Ding, Wei Zhan, Masayoshi Tomizuka, IEEE Robotics and Automation Letters (RA-L), DOI: 10.1109/LRA.2025.3551098.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/DDM_lag_framework.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DDM-Lag : A Diffusion-based Decision-making Model for Autonomous Vehicles with Lagrangian Safety Enhancement](https://ieeexplore.ieee.org/document/10752915)

**Jiaqi Liu**, Peng Hang, Xiaocong Zhao, Jianqiang Wang, Jian Sun, IEEE Transactions on Artificial Intelligence(TAI), DOI: 10.1109/TAI.2024.3497918.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/MAGADDPG.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Cooperative Decision-Making for CAVs at Unsignalized Intersections: A MARL Approach with Attention and Hierarchical Game Priors](https://ieeexplore.ieee.org/document/10774177)

**Jiaqi Liu**, Peng Hang, Xiaoxiang Na, Chao Huang, Jian Sun, IEEE Transactions on Intelligent Transportation Systems (TITS), DOI: 10.1109/TITS.2024.3503092, 2024.

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/MAPPO_PIS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MAPPO-PIS: A Multi-Agent Proximal Policy Optimization Method with Prior Intent Sharing for CAVs' Cooperative Decision-Making](https://arxiv.org/abs/2408.06656)

Yicheng Guo$^\star$, **Jiaqi Liu**$^\star$, Rongjie Yu, Peng Hang, Jian Sun, accepted by [ECCV 2024 MAAS Workshop](https://coop-intelligence.github.io/)(Oral).

</div>
</div>




# 🎖 Honors and Awards
- *2025.06* Outstanding Graduates from Shanghai(Top 1%).
- *2024.10* National Scholarship, Ministry of Education of China
- *2022.10* [Shanghai University Student Annual Character (Nomination Award)](https://edu.sh.gov.cn/xxgk2_zdgz_pxbz_01/20221019/a513dbcaca5e4dddb0a36cf00a5ff5b1.html)!
- *2022.06* Outstanding Graduates from Shanghai(Top 1%).
- *2021.12* National Scholarship, Ministry of Education of China
- *2021.05* [Tongji University Pursuit of Excellence Award](https://news.tongji.edu.cn/info/1008/77493.htm) (3/4450) !
- *2020.10* Best paper award of [Contemporary Undergraduate Mathematical Contest in Modeling (CUMCM)](http://www.mcm.edu.cn/html_cn/node/15767d638d52e1d38c64ea910de792d1.html) **(3/ 42000+)** !
- *2020.10* First Prize in the Shanghai College Students Transportation Innovation Competition
- *2020.5*  First Prize in Tongji University Mathematical Modeling Contest
- *2019.12* National Scholarship, Ministry of Education of China



# 📖 Educations
- *2025.08 - now*, PhD, UNC Chapel Hill, NC, US
- *2022.09 - 2025.06*, Master, Tongji University, Shanghai, China
- *2018.09 - 2022.06*, Bachelor, Tongji University, Shanghai, China (GPA: 4.89/5, rank: 1/163)

# 📚 Academic Services
## Reviews

- Conference Reviewer: NeurIPS, ICML, CVPR, ICCV, AAAI, ICRA, ITSC
- Journal Reviewer: IEEE Transactions on Intelligent Vehicles (TIV), IEEE Transactions on Intelligent Transportation Systems (TITS), IEEE Transactions on Neural Networks and Learning(TNNLS),IEEE Robotics and Automation Letters (RA-L), Journal of Field Robotics, IEEE Transactions on Industrial Informatics (TII), IEEE Transactions on Vehicular Technology (TVT), IEEE Transactions on Automation Science and Engineering (TASE), IEEE Internet of Things Journal, Nonlinear Dynamics, Journal of Advanced Transportation, Scientific Reports

##  Mentoring

- Yaofeng Su: Fudan University
- Kaiwen Xiong: Shanghai Jiao Tong University
- Carsen Sharkey: UNC Chapel Hill
- Yicheng Guo: Tongji University
- [Chengkai Xu](https://perfectxu88.github.io/): Tongji University
- Yuhang Zhang: Tongji University

## Teaching Assistant
- CS 790-183: Transfer Learning, UNC, Fall 2025
