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

I received my M.Eng. degree from Zhejiang University in March 2026, and will start my Ph.D. in Computer Science and Technology at Zhejiang University in September 2026, jointly trained with Shanghai AI Laboratory.

My research interests lie in **continual learning**, **large language models (LLMs)**, and **agents**. I am particularly interested in building agents that can learn from experience, retrieve and reason over knowledge, and improve through interaction over time.

My [Google Scholar profile](https://scholar.google.com/citations?user=CWLwlJwAAAAJ&hl=zh-CN) is available online. Citation statistics: <a href='https://scholar.google.com/citations?user=CWLwlJwAAAAJ&hl=zh-CN'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

<span class='anchor' id='news'></span>

# News

- *2026.09*: I will join the Ph.D. program in Computer Science and Technology at Zhejiang University, jointly trained with Shanghai AI Laboratory.
- *2026.03*: I received my M.Eng. degree from Zhejiang University.
- *2026*: **EvolveR** accepted to **ICML 2026**; **LeanRAG** accepted to **AAAI 2026**.
- *2025.02 - Present*: Research intern at Shanghai AI Laboratory, working on LLM agents, RAG, and continual learning.

<span class='anchor' id='publications'></span>

# Publications

## Agent

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/papers/evolver.png' alt="EvolveR" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EvolveR: Self-Evolving LLM Agents through an Experience-Driven Lifecycle](https://arxiv.org/abs/2510.16079)

**Rong Wu***, Xiaoman Wang*, Jianbiao Mei, Pinlong Cai, Daocheng Fu, Cheng Yang, Licheng Wen, Xuemeng Yang, Yufan Shen, et al. (* equal contribution)

[**Paper**](https://arxiv.org/abs/2510.16079) | [**Code**](https://github.com/Edaizi/EvolveR) | [**HuggingFace**](https://huggingface.co/papers/2510.16079)

- A closed-loop experience lifecycle that enables LLM agents to distill reusable strategic principles offline and retrieve them during online interaction.
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='images/papers/trainee-bench.png' alt="Trainee-Bench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[The Agent's First Day: Benchmarking Learning, Exploration, and Scheduling in the Workplace Scenarios](https://arxiv.org/abs/2601.08173)

Daocheng Fu*, Jianbiao Mei*, **Rong Wu***, Xuemeng Yang, Jia Xu, Ding Wang, Pinlong Cai, Yong Liu, Licheng Wen, Botian Shi. (* equal contribution)

[**Paper**](https://arxiv.org/abs/2601.08173) | [**Code**](https://github.com/KnowledgeXLab/EvoEnv) | [**HuggingFace**](https://huggingface.co/papers/2601.08173)

- Introduces Trainee-Bench, a dynamic benchmark for evaluating scheduling, exploration, and continual learning in workplace scenarios.
</div></div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/papers/kg-traces.png' alt="KG-Traces" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[KG-Traces: Enhancing Large Language Models with Knowledge Graph-Constrained Trajectory Reasoning and Attribution Supervision](https://arxiv.org/abs/2506.00783)

**Rong Wu**, Pinlong Cai, Jianbiao Mei, Licheng Wen, Tao Hu, Xuemeng Yang, Daocheng Fu, Botian Shi

[**Paper**](https://arxiv.org/abs/2506.00783) | [**Code**](https://github.com/Edaizi/KG-TRACES) | [**HuggingFace**](https://huggingface.co/papers/2506.00783)

- Supervises LLM reasoning with KG-constrained trajectories and attribution-aware explanations for traceable reasoning.
</div></div>

- `ACL 2026 Findings` [Learning on the Job: An Experience-Driven Self-Evolving Agent for Long-Horizon Tasks](https://arxiv.org/abs/2510.08002), Cheng Yang, Xuemeng Yang, Licheng Wen, Daocheng Fu, Jianbiao Mei, **Rong Wu**, Pinlong Cai, Yufan Shen, Ning Deng, Botian Shi, et al. [**Paper**](https://arxiv.org/abs/2510.08002) | [**Code**](https://github.com/KnowledgeXLab/MUSE) | [**HuggingFace**](https://huggingface.co/papers/2510.08002)
- `TMLR 2025` [O2-Searcher: A Searching-based Agent Model for Open-Domain Open-Ended Question Answering](https://arxiv.org/abs/2505.16582), Jianbiao Mei, Tao Hu, Daocheng Fu, Licheng Wen, Xuemeng Yang, **Rong Wu**, Pinlong Cai, Xinyu Cai, Xing Gao, Yu Yang, et al. [**Paper**](https://arxiv.org/abs/2505.16582) | [**Code**](https://github.com/KnowledgeXLab/O2-Searcher) | [**HuggingFace**](https://huggingface.co/papers/2505.16582)
- `arXiv 2025` [RE-Searcher: Robust Agentic Search with Goal-oriented Planning and Self-reflection](https://arxiv.org/abs/2509.26048), Daocheng Fu, Jianbiao Mei, Licheng Wen, Xuemeng Yang, Cheng Yang, **Rong Wu**, Tao Hu, Sheng Li, Yufan Shen, Xinyu Cai, et al. [**Paper**](https://arxiv.org/abs/2509.26048) | [**HuggingFace**](https://huggingface.co/papers/2509.26048)

## RAG

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='images/papers/leanrag.png' alt="LeanRAG" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[LeanRAG: Knowledge-Graph-based Generation with Semantic Aggregation and Hierarchical Retrieval](https://arxiv.org/abs/2508.10391)

Yaoze Zhang*, **Rong Wu***, Pinlong Cai, Xiaoman Wang, Guohang Yan, Song Mao, Ding Wang, Botian Shi. (* equal contribution)

[**Paper**](https://arxiv.org/abs/2508.10391) | [**Code**](https://github.com/RaZzzyz/LeanRAG) | [**HuggingFace**](https://huggingface.co/papers/2508.10391)

- A hierarchical KG-RAG framework with semantic aggregation and structure-guided retrieval to reduce redundancy.
</div></div>

## Ai4sci

- `Energy 2024` [A Transferable Federated Learning Approach for Wind Power Prediction Based on Active Privacy Clustering and Knowledge Merge](https://doi.org/10.1016/j.energy.2024.134044), Feiyun Cong, **Rong Wu**, Wei Zhong, Xiaojie Lin. [**Paper**](https://doi.org/10.1016/j.energy.2024.134044)
- `ASME 2024` [An Ultra-Short-Term Power Prediction Method for Wind Farms in Northwest China Based on Federated Learning](https://doi.org/10.1115/ES2024-131171), **Rong Wu**, Xiaojie Lin, Feiyun Cong, Wei Zhong. [**Paper**](https://doi.org/10.1115/ES2024-131171)

## Others

- `ICLR 2025` [Knowledge Graph Finetuning Enhances Knowledge Manipulation in Large Language Models](https://openreview.net/forum?id=oMFOKjwaRS), Hanzhu Chen, Xu Shen, Jie Wang, Zehao Wang, Qitan Lv, Junjie He, **Rong Wu**, Feng Wu, Jieping Ye. [**Paper**](https://openreview.net/forum?id=oMFOKjwaRS) | [**ICLR**](https://iclr.cc/virtual/2025/poster/28362)


<span class='anchor' id='education'></span>

# Education

- *2026.09 - *, Ph.D. in Computer Science and Technology, Zhejiang University (joint training with Shanghai AI Laboratory).
- *2023 - 2026.03*, M.Eng. in Smart Energy (Power Engineering), College of Excellent Engineers, Zhejiang University.
- *2019 - 2023*, B.Eng. in Energy and Power Engineering, Nanjing University of Aeronautics and Astronautics.

<span class='anchor' id='experience'></span>

# Experience

- *2025.02 - Present*, Research Intern, Shanghai AI Laboratory.
- *2023.12 - 2024.09*, Research Intern, Alibaba Cloud.
