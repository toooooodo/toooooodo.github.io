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

I'm Xiang Zhuang (庄祥), a Ph.D. student in Computer Science at [Zhejiang University (浙江大学)](https://www.zju.edu.cn/), advised by Professor [Huajun Chen (陈华钧)](https://person.zju.edu.cn/en/huajun) and [Qiang Zhang (张强)](https://person.zju.edu.cn/en/zhangqiang). I received my bachelor's degree in Software Engineering from Zhejiang University in 2020. My research interests lie in AI for Science (AI4Science), particularly in applying large language models (LLMs) to biomolecules. I received the 2025 CAAI Rising Scientist Honorable Mention (中国人工智能学会首届“潜力清源学者”), in recognition of achievements at the interdisciplinary frontiers of AI.



# 🔥 News
- *2025.06*: &nbsp;🎉🎉  I received the 2025 CAAI Rising Scientist Honorable Mention (中国人工智能学会首届“潜力清源学者”), awarded to only 10 recipients nationwide.
- *2025.05*: &nbsp;🎉🎉 Our paper [InstructBioMol](https://www.nature.com/articles/s42256-025-01064-0) was accepted to Nature Machine Intelligence.
- *2025.05*: &nbsp;🎉🎉 One paper was accepted to ACL 2025.
- *2025.04*: &nbsp;🎉🎉 I will give a tutorial on [Integrating Knowledge Graphs and Large Language Models for Advancing Scientific Research](https://icdcs2025.icdcs.org/tutorial-integrating-knowledge-graphs-and-large-language-models-for-advancing-scientific-research/) at ICDCS 2025. See you in Glasgow this July!
- *2025.01*: &nbsp;🎉🎉 One survey paper about [Scientific Large Language Models](https://dl.acm.org/doi/10.1145/3715318) was accepted to ACM Computing Surveys.
- *2024.10*: &nbsp;We released a preprint on a multimodal biomolecular large language model [InstructBioMol](https://arxiv.org/abs/2410.07919).
- *2024.09*: &nbsp;🎉🎉 One paper was accepted to NeurIPS 2024.
- *2024.06*: &nbsp;We released a preprint of a dataset and benchmark paper on [Scientific Knowledge Evaluation](https://github.com/HICAI-ZJU/SciKnowEval).



# 📝 Publications <font size=3>(* indicates co-first author)</font>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->


## Journal
- **Advancing Biomolecular Understanding and Design Following Human Instructions**<br>**Xiang Zhuang**, Keyan Ding, Tianwen Lyu, Yinuo Jiang, Xiaotong Li, Zhuoyi Xiang, Zeyuan Wang, Ming Qin, Kehua Feng, Jike Wang, Qiang Zhang, Huajun Chen<br>***Nature Machine Intelligence***, 2025<br>[\[paper\]](https://www.nature.com/articles/s42256-025-01064-0)[\[code\]](https://github.com/HICAI-ZJU/InstructBioMol)
- **Scientific large language models: A survey on biological & chemical domains**<br>Qiang Zhang, Keyang Ding, Tianwen Lyv, Xinda Wang, Qingyu Yin, Yiwen Zhang, Jing Yu, Yuhao Wang, Xiaotong Li, Zhuoyi Xiang, **Xiang Zhuang**, Zeyuan Wang, Ming Qin, Mengyao Zhang, Jinlu Zhang, Jiyu Cui, Renjun Xu, Hongyang Chen, Xiaohui Fan, Huabin Xing, Huajun Chen<br>***ACM Computing Surveys***, 2025<br>[\[paper\]](https://dl.acm.org/doi/10.1145/3715318)[\[code\]](https://github.com/HICAI-ZJU/Scientific-LLM-Survey)
- **Knowledge Graph-enhanced Molecular Contrastive Learning with Functional Prompt**<br>Yin Fang, Qiang Zhang, Ningyu Zhang, Zhuo Chen, **Xiang Zhuang**, Xin Shao, Xiaohui Fan, Huajun Chen<br> ***Nature Machine Intelligence***, 2023<br>[\[paper\]](https://www.nature.com/articles/s42256-023-00654-0)[\[code\]](https://github.com/HICAI-ZJU/KANO)
- **Benchmarking Knowledge-driven Zero-shot Learning**<br>Yuxia Geng, Jiaoyan Chen, **Xiang Zhuang**, Zhuo Chen, Jeff Z Pan, Juan Li, Zonggang Yuan, Huajun Chen<br>***Journal of Web Semantics***, 2023<br>[\[paper\]](https://www.sciencedirect.com/science/article/pii/S1570826822000415)[\[code\]](https://github.com/China-UK-ZSL/Resources_for_KZSL)
- **De Novo Analysis of Bulk RNA-seq Data at Spatially Resolved Single-cell Resolution**<br>Jie Liao\*, Jingyang Qian\*, Yin Fang\*, Zhuo Chen\*, **Xiang Zhuang\***, Ningyu Zhang, Xin Shao, Yining Hu, Penghui Yang, Junyun Cheng, Yang Hu, Lingqi Yu, Haihong Yang, Jinlu Zhang, Xiaoyan Lu, Li Shao, Dan Wu, Yue Gao, Huajun Chen, Xiaohui Fan<br>***Nature Communications** (Top 25 Life and Biological Sciences Articles of 2022)*, 2022<br>[\[paper\]](https://www.nature.com/articles/s41467-022-34271-z)[\[code\]](https://github.com/ZJUFanLab/bulk2space)
- **scDeepSort: a Pre-trained Cell-type Annotation Method for Single-cell Transcriptomics using Deep Learning with a Weighted Graph Neural Network**<br>Xin Shao, Haihong Yang, **Xiang Zhuang**, Jie Liao, Penghui Yang, Junyun Cheng, Xiaoyan Lu, Huajun Chen, Xiaohui Fan<br>***Nucleic Acids Research***, 2021<br>[\[paper\]](https://academic.oup.com/nar/article/49/21/e122/6368052)[\[code\]](https://github.com/ZJUFanLab/scDeepSort)

## Conference
- **Boosting LLM’s Molecular Structure Elucidation with Knowledge Enhanced Tree Search Reasoning**<br>**Xiang Zhuang**, Bin Wu, Jiyu Cui, Kehua Feng, Xiaotong Li, Huabin Xing, Keyan Ding, Qiang Zhang, Huajun Chen<br> ***ACL***, 2025<br>[\[paper\]](https://arxiv.org/abs/2506.23056)[\[code\]](https://github.com/HICAI-ZJU/K-MSE)
- **DePLM: Denoising Protein Language Models for Property Optimization**<br>Zeyuan Wang, Keyan Ding, Ming Qin, Xiaotong Li, **Xiang Zhuang**, Yu Zhao, Jianhua Yao, Qiang Zhang, Huajun Chen<br> ***NeurIPS***, 2024<br>[\[paper\]](https://proceedings.neurips.cc/paper_files/paper/2024/file/89af8e4eb696738f2c9e589522968a09-Paper-Conference.pdf)[\[code\]]()
- **StableMask: Refining Causal Masking in Decoder-only Transformer**<br>Qingyu Yin, Xuzheng He, **Xiang Zhuang**, Yu Zhao, Jianhua Yao, Xiaoyu Shen, Qiang Zhang<br> ***ICML***, 2024<br>[\[paper\]](https://arxiv.org/abs/2402.04779)[\[code\]](https://github.com/MikaStars39/StableMask)
- **Knowledge-aware Reinforced Language Models for Protein Directed Evolution**<br>Yuhao Wang, Qiang Zhang, Ming Qin, **Xiang Zhuang**, Xiaotong Li, Zhichen Gong, Zeyuan Wang, Yu Zhao, Jianhua Yao, Keyan Ding, Huajun Chen<br> ***ICML***, 2024<br>[\[paper\]](https://openreview.net/forum?id=MikandLqtW)[\[code\]]()
- **InstructProtein: Aligning Human and Protein Language via Knowledge Instruction**<br>Zeyuan Wang, Qiang Zhang, Keyan Ding, Ming Qin, **Xiang Zhuang**, Xiaotong Li, Huajun Chen<br> ***ACL***, 2024<br>[\[paper\]](https://arxiv.org/abs/2310.03269)[\[code\]](https://github.com/HICAI-ZJU/InstructProtein)
- **Enhancing Cross Text-Molecule Learning by Self-Augmentation**<br>Yinuo Jiang, **Xiang Zhuang**, Keyan Ding, Qiang Zhang, Huajun Chen<br> ***ACL Findings***, 2024<br>[\[paper\]]()[\[code\]]()
- **Learning Invariant Molecular Representation in Latent Discrete Space**<br>**Xiang Zhuang**, Qiang Zhang, Keyan Ding, Yatao Bian, Xiao Wang, Jingsong Lv, Hongyang Chen, Huajun Chen<br> ***NeurIPS***, 2023<br>[\[paper\]](https://arxiv.org/abs/2310.14170)[\[code\]](https://github.com/HICAI-ZJU/iMoLD)
- **Prompting Meta-Learned Hierarchical Graph Network for Molecular Property Prediction**<br>**Xiang Zhuang**, Keyan Ding, Yin Fang, Huajun Chen, Qiang Zhang<br> ***IEEE MedAI***, 2023<br>[\[paper\]](https://ieeexplore.ieee.org/abstract/document/10403216/)[\[code\]]()
- **Graph Sampling-based Meta-Learning for Molecular Property Prediction**<br>**Xiang Zhuang**, Qiang Zhang, Bin Wu, Keyan Ding, Yin Fang, Huajun Chen<br> ***IJCAI***, 2023<br>[\[paper\]](https://arxiv.org/abs/2306.16780)[\[code\]](https://github.com/HICAI-ZJU/GS-Meta)
- **Molecular Contrastive Learning with Chemical Element Knowledge Graph**<br>Yin Fang, Qiang Zhang, Haihong Yang, **Xiang Zhuang**, Shumin Deng, Wen Zhang, Ming Qin, Zhuo Chen, Xiaohui Fan, Huajun Chen<br>***AAAI***, 2022<br>[\[paper\]](https://arxiv.org/abs/2112.00544)[\[code\]](https://github.com/ZJU-Fangyin/KCL)


## Preprint
- **SciKnowEval: Evaluating Multi-level Scientific Knowledge of Large Language Models**<br>Kehua Feng, Keyan Ding, Weijie Wang, **Xiang Zhuang**, Zeyuan Wang, Ming Qin, Yu Zhao, Jianhua Yao, Qiang Zhang, Huajun Chen<br>[\[paper\]](https://arxiv.org/abs/2406.09098)[\[code\]](https://github.com/HICAI-ZJU/SciKnowEval)

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.2 - now*, &nbsp;&nbsp;&nbsp;  Ph.D., Computer science and technology, Zhejiang University.
- *2020.9 - 2023.1*, Master, Computer science and technology, Zhejiang University.
- *2016.9 - 2020.7*, Undergraduate, Software engineering, Zhejiang University. 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->