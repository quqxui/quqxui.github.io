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

I am currently a joint Ph.D. student in Data Science at [USTC](https://en.ustc.edu.cn/) and [CityU](https://www.cityu.edu.hk/), supervised by [Prof. Enhong Chen](http://staff.ustc.edu.cn/~cheneh/) and [Prof. Tong Xu](http://staff.ustc.edu.cn/~tongxu/) at BDAA Lab, and [Prof. Xiangyu Zhao](https://zhaoxyai.github.io/) at AML Lab. Prior to starting my doctoral studies, I received my B.S. degree in Intelligent Science and Technology from [XDU](https://en.xidian.edu.cn/) in 2021.

My research interests include **Agentic Post-training**, **Agent Memory**, **Reinforcement Learning**, **Retrieval-Augmented Generation**. 

Links: [Email](mailto:derongxu@mail.ustc.edu.cn), [Google Scholar](https://scholar.google.com.hk/citations?hl=zh-CN&user=3enGCo0AAAAJ), [GitHub](https://github.com/quqxui).



# 📝 Selected Publications

\* indicates equal contribution.

- From Single to Multi-Granularity: Toward Long-Term Memory Association and Selection of Conversational Agents  
  - **Derong Xu**, Yi Wen, Pengyue Jia, Yingyi Zhang, Wenlin Zhang, Yichao Wang, Huifeng Guo, Ruiming Tang, Xiangyu Zhao, Enhong Chen, Tong Xu (**ICLR 2026**)  
  \[[Paper](https://arxiv.org/abs/2505.19549)\|[Code](https://github.com/quqxui/MemGAS)\]

- Learning How and What to Memorize: Cognition-Inspired Two-Stage Optimization for Evolving Memory
  - **Derong Xu**, Shuochen Liu, Pengfei Luo, Pengyue Jia, Yingyi Zhang, Yi Wen, Yimin Deng, Wenlin Zhang, Enhong Chen, Xiangyu Zhao, Tong Xu (**ACL 2026**)   \[[Paper](https://arxiv.org/abs/2605.00702)\|[Code](https://github.com/Applied-Machine-Learning-Lab/ACL2026_MemCoE)\]

- ProEchoMem: Enhancing Long Video Understanding via Multi-Trace Probe-Echo Memory  
  - **Derong Xu**\*, Yanxin Chen\*, Wanyu Wang, Pengyue Jia, Chao Zhang, Maolin Wang, Yiqi Wang, Jipeng Qiang, Xuetao Wei, Hongzhi Yin, Tong Xu, Xiangyu Zhao  (**SIGIR 2026**)    \[[Paper]()\|[Code]()\]



- Bridging Relevance and Reasoning: Rationale Distillation in Retrieval-Augmented Generation  
  - Pengyue Jia\*, **Derong Xu**\*, Xiaopeng Li\*, Zhaocheng Du, Xiangyang Li, Xiangyu Zhao, Yichao Wang, Yuhao Wang, Huifeng Guo, Ruiming Tang (**ACL Findings 2025**)  
  \[[Paper](https://arxiv.org/abs/2412.08519)\|[Code](https://github.com/Applied-Machine-Learning-Lab/RADIO)\]


- Harnessing Large Language Models for Knowledge Graph Question Answering via Adaptive Multi-Aspect Retrieval-Augmentation  
  - **Derong Xu**, Xinhang Li, Ziheng Zhang, Zhenxi Lin, Zhihong Zhu, Zhi Zheng, Xian Wu, Xiangyu Zhao, Tong Xu, Enhong Chen (**AAAI 2025**)  
  \[[Paper](https://arxiv.org/abs/2412.18537)\|[Code](https://github.com/Applied-Machine-Learning-Lab/AMAR)\]

- Mitigating Hallucinations of Large Language Models in Medical Information Extraction via Contrastive Decoding  
  - **Derong Xu**, Ziheng Zhang, Zhihong Zhu, Zhenxi Lin, Qidong Liu, Xian Wu, Tong Xu, Xiangyu Zhao, Yefeng Zheng, Enhong Chen (**EMNLP Findings 2024**)  
  \[[Paper](https://arxiv.org/abs/2410.15702)\|[Code](https://github.com/quqxui/quqxui-AlternateCD)\]

- Editing Factual Knowledge and Explanatory Ability of Medical Large Language Models  
  - **Derong Xu**, Ziheng Zhang, Zhihong Zhu, Zhenxi Lin, Qidong Liu, Xian Wu, Tong Xu, Wanyu Wang, Yuyang Ye, Xiangyu Zhao, Enhong Chen, Yefeng Zheng (**CIKM 2024**)  
  \[[Paper](https://dl.acm.org/doi/10.1145/3627673.3679673)\|[Code](https://github.com/quqxui/MedLaSA)\]

- Large Language Models for Generative Information Extraction: A Survey  
  - **Derong Xu**, Wei Chen, Wenjun Peng, Chao Zhang, Tong Xu, Xiangyu Zhao, Xian Wu, Yefeng Zheng, Enhong Chen (**FCS 2024**)  
  \[[Paper](https://link.springer.com/article/10.1007/s11704-024-40555-y)\|[Code](https://github.com/quqxui/Awesome-LLM4IE-Papers)\]

- Multi-perspective Improvement of Knowledge Graph Completion with Large Language Models  
  - **Derong Xu**, Ziheng Zhang, Zhenxi Lin, Xian Wu, Zhihong Zhu, Tong Xu*, Xiangyu Zhao, Yefeng Zheng, Enhong Chen (**COLING 2024**)  
  \[[Paper](https://aclanthology.org/2024.lrec-main.1044/)\|[Code](https://github.com/quqxui/MPIKGC)\]

- Multimodal Biological Knowledge Graph Completion via Triple Co-attention Mechanism  
  - **Derong Xu**, Jingbo Zhou, Tong Xu*, Yuan Xia, Ji Liu, Enhong Chen, Dejing Dou (**ICDE 2023**)  
  \[[Paper](https://zhoujingbo.github.io/paper/2023MultimodalBiologicalICDE.pdf)\|[Code](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/research/CamE)\]

- Relation-enhanced Negative Sampling for Multimodal Knowledge Graph Completion  
  - **Derong Xu**, Tong Xu*, Shiwei Wu, Jingbo Zhou, Enhong Chen (**ACM MM 2022**)  
  \[[Paper](https://dl.acm.org/doi/10.1145/3503161.3548388)\|[Code](https://github.com/quqxui/MMRNS)\]

- Evoking User Memory: Personalizing LLM via Recollection-Familiarity Adaptive Retrieval  
  - Yingyi Zhang, Junyi Li, Wenlin Zhang, Pengyue Jia, Xianneng Li, Yichao Wang, **Derong Xu**, Yi Wen, Huifeng Guo, Yong Liu, Xiangyu Zhao (**ICLR 2026**)  
  \[[Paper](https://openreview.net/forum?id=f7p0F2X6XN)\|[Code](https://github.com/Applied-Machine-Learning-Lab/ICLR2026_RF-Mem)\]


- MLLM-I2W: Harnessing Multimodal Large Language Model for Zero-Shot Composed Image Retrieval  
  - Tong Bao, Che Liu, **Derong Xu**, Zhi Zheng, Tong Xu (**COLING 2025, Outstanding Paper Award, 5/1922**)

- More Edits, More Stable: Understanding the Lifelong Normalization in Sequential Model Editing  
  - Xin Ma, Wei Chen, Qi Liu, **Derong Xu**, Zhi Zheng, Tong Xu, Enhong Chen (**ICML 2026**)

- Evoking User Memory: Personalizing LLM via Recollection-Familiarity Adaptive Retrieval  
  - Yingyi Zhang, Junyi Li, Wenlin Zhang, Pengyue Jia, Xianneng Li, Yichao Wang, **Derong Xu**, Yi Wen, Huifeng Guo, Yong Liu, Xiangyu Zhao (**ICLR 2026**)

- Personalize Before Retrieve: LLM-based Personalized Query Expansion for User-Centric Retrieval  
  - Yingyi Zhang, Pengyue Jia, **Derong Xu**, Yi Wen, Xianneng Li, Yichao Wang, Wenlin Zhang, Xiaopeng Li, Weinan Gan, Huifeng Guo, Yong Liu, Xiangyu Zhao (**AAAI 2026**)

- To Search or Not to Search: Aligning the Decision Boundary of Deep Search Agents via Causal Intervention  
  - Wenlin Zhang, Kuicai Dong, Junyi Li, Yingyi Zhang, Xiaopeng Li, Pengyue Jia, Yi Wen, **Derong Xu**, Maolin Wang, Yichao Wang, Yong Liu, Xiangyu Zhao (**WWW 2026**)

- SAGE: Global Semantic Alignment with LLMs for Long-Tail Sequential Recommendation  
  - Maolin Wang, Tongshu Bian, Ziyan Wang, Xiaotong Jiang, Binhao Wang, **Derong Xu**, Wanyu Wang, Ruocheng Guo, Xiangyu Zhao (**WWW 2026**)

- A Survey of Personalization: From RAG to Agent  
  - Xiaopeng Li, Pengyue Jia, **Derong Xu**, Yi Wen, Yingyi Zhang, Wenlin Zhang, Wanyu Wang, Yichao Wang, Zhaocheng Du, Xiangyang Li, Yong Liu, Huifeng Guo, Ruiming Tang, Xiangyu Zhao (**TOIS 2026**)

- AdapTime: Enabling Adaptive Temporal Reasoning in Large Language Models  
  - Yimin Deng, Yejing Wang, Zhenxi Lin, Zichuan Fu, Guoshuai Zhao, **Derong Xu**, Yefeng Zheng, Xiangyu Zhao, Xian Wu, Li Zhu, Xueming Qian (**ACL 2026**)

- MultiDx: A Multi-Source Knowledge Integration Framework towards Diagnostic Reasoning  
  - Yimin Deng, Zhenxi Lin, Yejing Wang, Guoshuai Zhao, Pengyue Jia, Zichuan Fu, **Derong Xu**, Yefeng Zheng, Xiangyu Zhao, Li Zhu, Xian Wu, Xueming Qian (**ACL 2026**)

- Process vs. Outcome Reward: Which is Better for Agentic RAG Reinforcement Learning  
  - Wenlin Zhang, Xiangyang Li, Kuicai Dong, Yichao Wang, Pengyue Jia, Xiaopeng Li, Yingyi Zhang, **Derong Xu**, Zhaocheng Du, Huifeng Guo, Ruiming Tang, Xiangyu Zhao (**NeurIPS 2025**)

- A Multi-Expert Structural-Semantic Hybrid Framework for Unveiling Historical Patterns in Temporal Knowledge Graphs  
  - Yimin Deng, Yuxia Wu, Yejing Wang, Guoshuai Zhao, Li Zhu, Qidong Liu, **Derong Xu**, Zichuan Fu, Xian Wu, Yefeng Zheng, Xiangyu Zhao, Xueming Qian (**ACL 2025**)

- Measure Domain's Gap: A Similar Domain Selection Principle for Multi-Domain Recommendation  
  - Yi Wen, Yue Liu, **Derong Xu**, Huishi Luo, Pengyue Jia, Yiqing Wu, Siwei Wang, Ke Liang, Maolin Wang, Yiqi Wang, Fuzhen Zhuang, Xiangyu Zhao (**KDD 2025**)

- LSRP: A Leader-Subordinate Retrieval Framework for Privacy-Preserving Cloud-Device Collaboration  
  - Yingyi Zhang, Pengyue Jia, Xianneng Li, **Derong Xu**, Maolin Wang, Yichao Wang, Zhaocheng Du, Huifeng Guo, Yong Liu, Ruiming Tang, Xiangyu Zhao (**KDD 2025**)

- Visualization Recommendation with Prompt-based Reprogramming of Large Language Models  
  - Xinhang Li, Jingbo Zhou, Wei Chen, **Derong Xu**, Tong Xu, Enhong Chen (**ACL 2024**)

- Alignment before Awareness: Towards Visual Question Localized-Answering in Robotic Surgery via Optimal Transport and Answer Semantics  
  - Zhihong Zhu, Yunyan Zhang, Xuxin Cheng, Zhiqi Huang, **Derong Xu**, Xian Wu, Yefeng Zheng (**LREC-COLING 2024**)

- TFCD: Towards Multi-modal Sarcasm Detection via Training-Free Counterfactual Debiasing  
  - Zhihong Zhu, Xianwei Zhuang, Yunyan Zhang, **Derong Xu**, Guimin Hu, Xian Wu, Yefeng Zheng (**IJCAI 2024**)

- When MOE Meets LLMs: Parameter Efficient Fine-tuning for Multi-task Medical Applications  
  - Qidong Liu, Xian Wu, Xiangyu Zhao, Yuanshao Zhu, **Derong Xu**, Feng Tian, Yefeng Zheng (**SIGIR 2024**)

- Large Language Model based Long-tail Query Rewriting in Taobao Search  
  - Wenjun Peng, Guiyang Li, Yue Jiang, Zilong Wang, Dan Ou, Xiaoyi Zeng, **Derong Xu**, Tong Xu, Enhong Chen (**WWW 2024**)

- Non-IID always Bad? Semi-Supervised Heterogeneous Federated Learning with Local Knowledge Enhancement  
  - Chao Zhang, Fangzhao Wu, Jingwei Yi, **Derong Xu**, Yang Yu, Jindong Wang, Yidong Wang, Tong Xu, Xing Xie, Enhong Chen (**CIKM 2023**)

- Unified QA-aware Knowledge Graph Generation Based on Multi-modal Modeling  
  - Penggang Qin, Jiarui Yu, Yan Gao, **Derong Xu**, Yunkai Chen, Shiwei Wu, Tong Xu, Enhong Chen, Yanbin Hao (**ACM MM 2022**)

# 🎖 Honors and Awards

- **Peter Ho Conference Scholarships (Top 10)**, 2025–2026
- **National Scholarship**, 2023
- **Third Prize**, CCKS 2022: Multimodal E-commerce Knowledge Graph Link Prediction, 2022
- **Shaanxi Provincial Outstanding Graduate (Top 1%)**, 2021
- **Goodix Scholarship & First-Class Scholarship**, 2021
- **National Scholarship (Undergraduate)**, 2018 and 2020
- **Gold Prize**, China International College Students’ Innovation Competition, 2020
- **Finalist (Top 1%)**, Mathematical Contest in Modeling (MCM/ICM), 2020



# 💻 Internships

- **2023/09–2024/09** ***Tencent Youtu Lab, Tianyuan Research Center, Shenzhen*** — *Research Intern*  
  - Worked on **Retrieval-Augmented Generation** and **LLM Hallucination in Medical**.

- **2022/10–2023/02** ***Microsoft Research Asia, Social Computing Group, Beijing*** — *Research Intern*  
  - Worked on **Knowledge-empowered News Recommendation**.

- **2021/03–2021/10** ***Baidu Research, Business Intelligence Lab, Beijing*** — *Research Intern*  
  - Worked on **Multimodal Knowledge Graph Completion**.



# Services

### Conference Reviewer
- **2026**: ICLR, ICML, ACL, KDD, CVPR, AAAI, SIGIR, ECCV, WSDM
- **2025**: ACL, KDD, SIGIR, ACMMM, EMNLP
- **2024**: ACL, ACMMM

### Journal Reviewer
- **IEEE Transactions on Big Data (TBD)**
- **IEEE Transactions on Knowledge and Data Engineering (TKDE)**

