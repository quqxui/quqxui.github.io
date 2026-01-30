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

# About Me

I am currently a joint PhD student at [USTC](https://en.ustc.edu.cn/) and [CityU](https://www.cityu.edu.hk/), supervised by [Prof.Enhong Chen](http://staff.ustc.edu.cn/~cheneh/) and [Prof.Tong Xu](http://staff.ustc.edu.cn/~tongxu/) at BDAA Lab, and [Prof.Xiangyu Zhao](https://zhaoxyai.github.io/) at AML lab. Prior to starting my doctoral studies, I received my Bachelor degree in Intelligent Science and Technology from [XDU](https://en.xidian.edu.cn/) in 2021.

Links: [Google Scholar](https://scholar.google.com.hk/citations?hl=zh-CN&user=3enGCo0AAAAJ), [GitHub](https://github.com/quqxui).

My research interests focus on Agent Memory, Large Language Models, Knowledge Graph, and Multimodal Learning.



# 📝 Selected Publications

- From Single to Multi-Granularity: Toward Long-Term Memory Association and Selection of Conversational Agents
  - **Derong Xu**, Yi Wen, Pengyue Jia, Yingyi Zhang, Wenlin Zhang, Yichao Wang, Huifeng Guo, Ruiming Tang, Xiangyu Zhao, Enhong Chen, Tong Xu (**ICLR 2026**)  
    \[[Paper](https://arxiv.org/abs/2505.19549)\|[Code](https://github.com/quqxui/MemGAS)\]

- Evoking User Memory: Personalizing LLM via Recollection-Familiarity Adaptive Retrieval
  - Yingyi Zhang, Junyi Li, Wenlin Zhang, Pengyue Jia, Xianneng Li, Yichao Wang, **Derong Xu**, Yi Wen, Huifeng Guo, Yong Liu, Xiangyu Zhao (**ICLR 2026**)  
    \[[Paper](https://openreview.net/forum?id=f7p0F2X6XN)\|[Code](https://github.com/Applied-Machine-Learning-Lab/ICLR2026_RF-Mem)\]

- Bridging Relevance and Reasoning: Rationale Distillation in Retrieval-Augmented Generation
  - Pengyue Jia\*, **Derong Xu**\*, Xiaopeng Li\*, Zhaocheng Du, Xiangyang Li, Xiangyu Zhao, Yichao Wang, Yuhao Wang, Huifeng Guo, Ruiming Tang (**ACL'2025 Findings**) \[[Paper](https://arxiv.org/abs/2412.08519)\|[Code](https://github.com/Applied-Machine-Learning-Lab/RADIO)\]

- MLLM-I2W: Harnessing Multimodal Large Language Model for Zero-Shot Composed Image Retrieval
  - Tong Bao, Che Liu, **Derong Xu**, Zhi Zheng, Tong Xu (**COLING'2025, Outstanding Paper Award, 5/1922**)
  
- Harnessing Large Language Models for Knowledge Graph Question Answering via Adaptive Multi-Aspect Retrieval-Augmentation
  - **Derong Xu**, Xinhang Li, Ziheng Zhang, Zhenxi Lin, Zhihong Zhu, Zhi Zheng, Xian Wu, Xiangyu Zhao, Tong Xu, Enhong Chen (**AAAI'2025**) \[[Paper](https://arxiv.org/abs/2412.18537)\|[Code](https://github.com/Applied-Machine-Learning-Lab/AMAR)\]

- Mitigating Hallucinations of Large Language Models in Medical Information Extraction via Contrastive Decoding
  - **Derong Xu**, Ziheng Zhang, Zhihong Zhu, Zhenxi Lin, Qidong Liu, Xian Wu, Tong Xu, Xiangyu Zhao, Yefeng Zheng, Enhong Chen (**EMNLP'2024 Findings**)  \[[Paper](https://arxiv.org/abs/2410.15702)\|[Code](https://github.com/quqxui/quqxui-AlternateCD)\]

- Editing Factual Knowledge and Explanatory Ability of Medical Large Language Models
  - **Derong Xu**, Ziheng Zhang, Zhihong Zhu, Zhenxi Lin, Qidong Liu, Xian Wu, Tong Xu, Wanyu Wang, Yuyang Ye, Xiangyu Zhao, Enhong Chen, Yefeng Zheng (**CIKM'24**) \[[Paper](https://dl.acm.org/doi/10.1145/3627673.3679673)\|[Code](https://github.com/quqxui/MedLaSA)\]

- Large Language Models for Generative Information Extraction: A Survey
  - **Derong Xu**, Wei Chen, Wenjun Peng, Chao Zhang, Tong Xu, Xiangyu Zhao, Xian Wu, Yefeng Zheng, Enhong Chen (**FCS'24**) \[[Paper](https://link.springer.com/article/10.1007/s11704-024-40555-y)\|[Code](https://github.com/quqxui/Awesome-LLM4IE-Papers)\]

- Multi-perspective Improvement of Knowledge Graph Completion with Large Language Models
  - **Derong Xu**, Ziheng Zhang, Zhenxi Lin, Xian Wu, Zhihong Zhu, Tong Xu*, Xiangyu Zhao, Yefeng Zheng and Enhong Chen (**COLING'24**) \[[Paper](https://aclanthology.org/2024.lrec-main.1044/)\|[Code](https://github.com/quqxui/MPIKGC)\]

- Multimodal Biological Knowledge Graph Completion via Triple Co-attention Mechanism
  - **Derong Xu**, Jingbo Zhou, Tong Xu*, Yuan Xia, Ji Liu, Enhong Chen, Dejing Dou (**ICDE'23**) \[[Paper](https://zhoujingbo.github.io/paper/2023MultimodalBiologicalICDE.pdf)\|[Code](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/research/CamE)\]

- Relation-enhanced Negative Sampling for Multimodal Knowledge Graph Completion
  - **Derong Xu**, Tong Xu*, Shiwei Wu, Jingbo Zhou, Enhong Chen (**ACM MM'22**) \[[Paper](https://dl.acm.org/doi/10.1145/3503161.3548388)\|[Code](https://github.com/quqxui/MMRNS)\]


<!--
Xinhang Li, Jingbo Zhou, Wei Chen, **Derong Xu**, Tong Xu, Enhong Chen, Visualization Recommendation with Prompt-based Reprogramming of Large Language Models, In Proceedings of the 62nd Annual Meeting of the Association for Computational Linguistics (**ACL'24**), Bangkok, Thailand, 2024, Accepted.

Qidong Liu, Xian Wu, Xiangyu Zhao, Yuanshao Zhu, **Derong Xu**, Feng Tian, Yefeng Zheng, When MOE Meets LLMs: Parameter Efficient Fine-tuning for Multi-task Medical Applications, Proceedings of the 47th International ACM SIGIR Conference on Research and Development in Information Retrieval (**SIGIR'24**). 

Wenjun Peng, Guiyang Li, Yue Jiang, Zilong Wang, Dan Ou, Xiaoyi Zeng, **Derong Xu**, Tong Xu, Enhong Chen, Large Language Model based Long-tail Query Rewriting in Taobao Search, In Proceedings of the Web Conference 2024 (**WWW'24**), Singapore, 2024, Accepted.

Zhihong Zhu, Xianwei Zhuang, Yunyan Zhang, **Derong Xu**, Guimin Hu, Xian Wu, Yefeng Zheng, TFCD: Towards Multi-modal Sarcasm Detection via Training-Free Counterfactual Debiasing, Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence (**IJCAI'24**).

Zhihong Zhu, Yunyan Zhang, Xuxin Cheng, Zhiqi Huang, **Derong Xu**, Xian Wu, Yefeng Zheng, Alignment before Awareness: Towards Visual Question Localized-Answering in Robotic Surgery via Optimal Transport and Answer Semantics, Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (**COLING'24**).


Chao Zhang, Fangzhao Wu, Jingwei Yi, **Derong Xu**, Yang Yu, Jindong Wang, Yidong Wang, Tong Xu, Xing Xie, Enhong Chen, Non-IID always Bad? Semi-Supervised Heterogeneous Federated Learning with Local Knowledge Enhancement, In Proceedings of the 32nd ACM International Conference on Information and Knowledge Management (**CIKM'23**), Birmingham, UK, 2023, Accepted.


Penggang Qin, Jiarui Yu, Yan Gao, **Derong Xu**, Yunkai Chen, Shiwei Wu, Tong Xu*, Yanbin Hao, Enhong Chen, Unified QA-aware Knowledge Graph Generation Based on Multi-modal Modeling, In Proceedings of the 30th ACM International Conference on Multimedia (**ACM MM'22**), Lisbon, Portugal, 2022, Accepted.

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

-->

# 💻 Internships
- **2021/02-2021/10** ***Baidu*** *Research Intern*
- **2022/10-2023/02** ***Microsoft*** *Research Intern*
- **2023/09-2024/09** ***Tencent*** *Research Intern*

# Services、
- 2026: ICLR, ICML, ACL, KDD, CVPR, AAAI, SIGIR, ECCV, WSDM
- 2025: ACL, KDD, SIGIR, ACMMM, EMNLP
- 2024: ACL, ACMMM
