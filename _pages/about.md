---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
  - /publications/
  - /honours-awards/
  - /cv/
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, I am **Hengzhe Zhang**. I am currently a Postdoctoral Research Fellow in Artificial Intelligence at the [Evolutionary Computation Research Group (ECRG)](https://ecs.wgtn.ac.nz/Groups/ECRG/WebHome), [School of Engineering and Computer Science](https://www.wgtn.ac.nz/engineering/school-of-engineering-and-computer-science), Victoria University of Wellington. I obtained my Ph.D. in Artificial Intelligence from Victoria University of Wellington in 2025 under the supervision of Prof. [Mengjie Zhang](https://scholar.google.co.nz/citations?user=hLvGrrkAAAAJ&hl=en) and Prof. [Bing Xue](https://scholar.google.com/citations?user=RILgdb4AAAAJ&hl=en). My research mainly focuses on **Interpretable Machine Learning, Explainable AI, and AI for Business/Healthcare**, with contributions in:

+ **Interpretable & Explainable AI**: I develop transparent, human-readable AI models grounded in symbolic regression and automated feature engineering, with publications in top venues including ICML, ICLR (Spotlight), and IEEE TEVC (ABS/AJG 4 ×6 as first author).
+ **Automated Machine Learning**: I design evolutionary and LLM-based methods for automated feature construction and ensemble learning, maintaining open-source tools with 150+ community stars ([Evolutionary Forest](https://github.com/zhenlingcn/EvolutionaryForest)).
+ **AI for Business/Healthcare**: I have applied interpretable ML to financial services and healthcare, developing auditable decision support systems for business analytics and operations.

张恒哲，现为新西兰惠灵顿维多利亚大学人工智能博士后研究员，2025年获人工智能博士学位。研究方向为可解释机器学习、可解释人工智能与商业/医疗健康智能，在 ICML、ICLR Spotlight、IEEE TEVC（ABS/AJG 4，第一作者×6）等期刊与会议发表多篇论文，并维护 150+ stars 的开源项目 Evolutionary Forest。

# 🔥 News

- *2026.06*: &nbsp;One ICML'26 paper on contrastive symbolic regression has been accepted.
- *2026.06*: &nbsp;Two PPSN'26 papers on symbolic regression and genetic programming have been accepted.
- *2026.02*: &nbsp;One AAAI'26 paper on pathology VLMs has been accepted (co-first author).
- *2025.09*: &nbsp;Started as Postdoctoral Research Fellow at Victoria University of Wellington.
- *2025.05*: &nbsp;One ICLR'25 paper has been accepted as **Spotlight** (RAG-SR: Retrieval-Augmented Generation for Neural Symbolic Regression).

# 📝 Publications

You can also find my articles on [Google Scholar](https://scholar.google.com/citations?user=hYyeZMUAAAAJ&hl=en).

**Selected Publications**

- `ICML'26` Contrastive Symbolic Regression: Aligned Representations, Adaptive Prediction, and Diverse Ensembles, **Hengzhe Zhang**, et al.
- `PPSN'26` Adaptive Protection for Evolutionary Feature Construction in Symbolic Regression with Application to Credit Classification, **Hengzhe Zhang**, Qi Chen, Bing Xue, Lean Yu, Wolfgang Banzhaf, Mengjie Zhang **(CORE A)**
- `PPSN'26` Benchmarking Zero-Shot LLM-Generated Parent Selection in Genetic Programming for Symbolic Regression, **Hengzhe Zhang**, Qi Chen, Bing Xue, Wolfgang Banzhaf, Mengjie Zhang **(CORE A)**
- `ICLR'25 Spotlight` [RAG-SR: Retrieval-Augmented Generation for Neural Symbolic Regression](https://openreview.net/), **Hengzhe Zhang**, et al.
- `AAAI'26` Patho-AgenticRAG: Towards Multimodal Agentic Retrieval-Augmented Generation for Pathology VLMs via Reinforcement Learning, Wenchuan Zhang, Jingru Guo, **Hengzhe Zhang** (co-first author), et al.
- `IEEE TEVC'25` LAS-GP: Harnessing Large Semantic Libraries for Evolutionary Feature Construction in Symbolic Regression, **Hengzhe Zhang**, et al. **(ABS/AJG 4, IF: 12)**
- `IEEE TEVC'25` Enhancing Generalization in Evolutionary Feature Construction for Symbolic Regression through Vicinal Jensen Gap Minimization, **Hengzhe Zhang**, et al. **(ABS/AJG 4, IF: 12)**
- `IEEE TEVC'24` Modular multi-tree genetic programming for evolutionary feature construction for regression, **Hengzhe Zhang**, et al. **(ABS/AJG 4, IF: 12)**
- `IEEE TEVC'23` [SR-Forest: A Genetic Programming-based Heterogeneous Ensemble Learning Method](https://ieeexplore.ieee.org/), **Hengzhe Zhang**, Aimin Zhou, Qi Chen, Bing Xue, Mengjie Zhang **(ABS/AJG 4, IF: 12)**
- `SWEVO'22` [PS-Tree: A Piecewise Symbolic Regression Tree](https://www.sciencedirect.com/science/article/pii/S2210650222000335), **Hengzhe Zhang**, Aimin Zhou, Hong Qian, Hu Zhang **(IF: 8.2)**
- `IEEE TEVC'21` [An Evolutionary Forest for Regression](https://ieeexplore.ieee.org/document/9656554), **Hengzhe Zhang**, Aimin Zhou, Hu Zhang **(ABS/AJG 4, IF: 12)**
- `GECCO'24` Bias-Variance Decomposition: An Effective Tool to Improve Generalization of Genetic Programming-based Evolutionary Feature Construction for Regression, **Hengzhe Zhang**, et al. **(CORE A)**
- `PPSN'24` P-Mixup: Improving Generalization Performance of Evolutionary Feature Construction with Pessimistic Vicinal Risk Minimization, **Hengzhe Zhang**, et al. **(CORE A)**

**Refereed Journal Articles**

- **Hengzhe Zhang**, et al. "LLM-Meta-SR: In-Context Learning for Evolving Selection Operators in Symbolic Regression." *IEEE Transactions on Evolutionary Computation*, 2026. **(IF: 12, ABS/AJG 4)**
- **Hengzhe Zhang**, et al. "LAS-GP: Harnessing Large Semantic Libraries for Evolutionary Feature Construction in Symbolic Regression." *IEEE Transactions on Evolutionary Computation*, 2025. **(IF: 12, ABS/AJG 4)**
- **Hengzhe Zhang**, et al. "Enhancing Generalization in Evolutionary Feature Construction for Symbolic Regression through Vicinal Jensen Gap Minimization." *IEEE Transactions on Evolutionary Computation*, 2025. **(IF: 12, ABS/AJG 4)**
- Hongbo Zhao, **Hengzhe Zhang**, et al. "SRLinear: Lightweight Long-Term Time Series Forecasting via Symbolic Regression." *IEEE Transactions on Artificial Intelligence*, 2025.
- **Hengzhe Zhang**, et al. "Adaptive complexity knee point selection in multi-objective genetic programming for improving generalization of evolutionary feature construction in regression." *Genetic Programming and Evolvable Machines*, 26.2 (2025): 28. **(IF: 1.7)**
- **Hengzhe Zhang**, et al. "Modular multi-tree genetic programming for evolutionary feature construction for regression." *IEEE Transactions on Evolutionary Computation*, 2024. **(IF: 12, ABS/AJG 4)**
- **Hengzhe Zhang**, et al. "A semantic-based hoist mutation operator for evolutionary feature construction in regression." *IEEE Transactions on Evolutionary Computation*, 2024. **(IF: 12, ABS/AJG 4)**
- **Hengzhe Zhang**, et al. "A geometric semantic macro-crossover operator for evolutionary feature construction in regression." *Genetic Programming and Evolvable Machines*, 25.1 (2024): 2. **(IF: 1.7)**
- **Hengzhe Zhang**, Aimin Zhou, Qi Chen, Bing Xue, and Mengjie Zhang. "SR-Forest: A Genetic Programming-based Heterogeneous Ensemble Learning Method." *IEEE Transactions on Evolutionary Computation*, 2023. **(IF: 12, ABS/AJG 4)**
- **Hengzhe Zhang**, et al. "MAP-Elites for Genetic Programming-Based Ensemble Learning: An Interactive Approach [AI-eXplained]." *IEEE Computational Intelligence Magazine*, 18.4 (2023): 62-63. **(IF: 11.2)**
- **Hengzhe Zhang**, Aimin Zhou, Hong Qian, and Hu Zhang. "[PS-Tree: A Piecewise Symbolic Regression Tree](https://www.sciencedirect.com/science/article/pii/S2210650222000335)." *Swarm and Evolutionary Computation*, Elsevier, 2022. **(IF: 8.2)**
- **Hengzhe Zhang**, Aimin Zhou, and Hu Zhang. "[An Evolutionary Forest for Regression](https://ieeexplore.ieee.org/document/9656554)." *IEEE Transactions on Evolutionary Computation*, 2021. **(IF: 12, ABS/AJG 4)**
- **Hengzhe Zhang**, Aimin Zhou, and Xin Lin. "Interpretable policy derivation for reinforcement learning based on evolutionary feature synthesis." *Complex & Intelligent Systems*, 6.3 (2020): 741-753. **(IF: 5.0)**

**Refereed Conference Articles**

- **Hengzhe Zhang**, et al. "Contrastive Symbolic Regression: Aligned Representations, Adaptive Prediction, and Diverse Ensembles." *International Conference on Machine Learning (ICML)*, 2026. **(CORE A\*)**
- Wenchuan Zhang, Jingru Guo, **Hengzhe Zhang** (co-first author), et al. "Patho-AgenticRAG: Towards Multimodal Agentic Retrieval-Augmented Generation for Pathology VLMs via Reinforcement Learning." *AAAI*, 2026. **(CORE A\*)**
- **Hengzhe Zhang**, et al. "RAG-SR: Retrieval-Augmented Generation for Neural Symbolic Regression." *ICLR*, 2025. **(Spotlight, CORE A\*)**
- **Hengzhe Zhang**, Qi Chen, Bing Xue, Lean Yu, Wolfgang Banzhaf, and Mengjie Zhang. "Adaptive Protection for Evolutionary Feature Construction in Symbolic Regression with Application to Credit Classification." *PPSN*, 2026. **(CORE A)**
- **Hengzhe Zhang**, Qi Chen, Bing Xue, Wolfgang Banzhaf, and Mengjie Zhang. "Benchmarking Zero-Shot LLM-Generated Parent Selection in Genetic Programming for Symbolic Regression." *PPSN*, 2026. **(CORE A)**
- **Hengzhe Zhang**, et al. "Micro-Step Time-Series Regression: Insights from System Identification Using Symbolic Regression." *EuroGP*, 2025. **(CORE B)**
- **Hengzhe Zhang**, et al. "A General Feature-Informed Crossover for Two-Stage Feature Selection in Symbolic Regression." *IEEE CEC*, 2025. **(CORE B)**
- **Hengzhe Zhang**, et al. "P-Mixup: Improving Generalization Performance of Evolutionary Feature Construction with Pessimistic Vicinal Risk Minimization." *PPSN*, 2024. **(CORE A)**
- **Hengzhe Zhang**, et al. "Bias-Variance Decomposition: An Effective Tool to Improve Generalization of Genetic Programming-based Evolutionary Feature Construction for Regression." *GECCO*, 2024. **(CORE A)**
- **Hengzhe Zhang**, et al. "Improving Generalization of Evolutionary Feature Construction with Minimal Complexity Knee Points in Regression." *EuroGP*, 2024. **(CORE B)**
- **Hengzhe Zhang**, Qi Chen, Alberto Tonda, Bing Xue, Wolfgang Banzhaf, and Mengjie Zhang. "MAP-Elites with Cosine-Similarity for Evolutionary Ensemble Learning." *EuroGP*, 2023. **(CORE B)**
- **Hengzhe Zhang**, Qi Chen, Bing Xue, Wolfgang Banzhaf, and Mengjie Zhang. "A Double Lexicase Selection Operator for Bloat Control in Evolutionary Feature Construction for Regression." *GECCO*, 2023. **(CORE A)**
- **Hengzhe Zhang**, et al. "Automatically Choosing Selection Operator Based on Semantic Information in Evolutionary Feature Construction." *PRICAI*, 2023. **(CORE B)**
- **Hengzhe Zhang**, Aimin Zhou. "RL-GEP: Symbolic Regression via Gene Expression Programming and Reinforcement Learning." *IJCNN*, 2021. **(CORE B)**

# 🎖 Honors and Awards

- *2024.07* First Prize, GECCO Interpretable Control Competition
- *2023.07* First Prize, GECCO Interpretable Symbolic Regression Competition
- *2022.05* Honorable Mention, CVPR NAS Performance Prediction Track (4th out of 48)
- *2022* Distinguished Graduate of Shanghai (上海市优秀毕业生)
- *2020.10* Wisdom Scholarship, East China Normal University (华东师范大学智慧奖学金)
- *2020.10* Second Prize, China Graduate Mathematical Modeling Contest (中国研究生数学建模竞赛, Top 15%)
- *2020.09* First Prize, ZA Insurance Hackathon, Machine Learning Track (众安保险黑客马拉松·机器学习赛道, 1st out of 71, [报道](https://wenhui.whb.cn/third/yidian/202010/11/374489.html))
- *2018.05* National First Prize, Blue Bridge Cup JAVA Track (蓝桥杯全国软件和信息技术专业人才大赛·Java B组, Top 5%)
- *2017.10* Bronze Award, ACM-ICPC Xi'an Regional Competition

# 📖 Educations

- *2022.01 – 2025*, Ph.D. in Artificial Intelligence, Victoria University of Wellington, New Zealand. Supervisors: Prof. Mengjie Zhang, Prof. Bing Xue.
- *2019.09 – 2022.06*, M.Sc. in Computer Science, East China Normal University, China. Supervisor: Prof. Aimin Zhou. Double First-Class University (QS Asian University Ranking: 64).
- *2015.09 – 2019.06*, B.Sc. in Software Engineering, Xiangtan University, China. Double First-Class University (QS Asian University Ranking: 307).

# 💻 Open Source Projects

- **[Evolutionary Forest](https://github.com/zhenlingcn/EvolutionaryForest)** (150+ Stars, IEEE TEVC 2021/2023/2025, ICLR 2025) — An interpretable automated feature engineering framework using evolutionary algorithms and large language models.
- **[PS-Tree](https://github.com/hengzhe-zhang/PS-Tree)** (30+ Stars, SWEVO 2022) — A toolkit for interpretable, piecewise symbolic regression.
- **[scikit-obliquetree](https://github.com/hengzhe-zhang/scikit-obliquetree)** (15+ Stars) — An oblique decision tree framework with three oblique decision tree algorithms.
