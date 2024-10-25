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


My primary research interests lie in knowledge acquisition, knowledge representation, and knowledge reasoning based on deep learning techniques. The ultimate goal of my research is to develop an artificial intelligence (AI) machine that can perceive, reason, and plan in real-world scenarios like humans. The research fields involve: Knowledge Graph (KG), Logical reasoning, and Large Language Model (LLM). Moving forward, my focus will be on exploring the potential of AI in multimodal healthcare and education applications.

I currently work as a Research Fellow in NUS. For my full (and timely) publication list, please refer to my Google scholar <a href='https://scholar.google.com/citations?user=k8BKz0MAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

***I am currently in the job market. If there are any available positions, please feel free to contact me.***

<!-- https://img.shields.io/badge/Google%20Scholar-Yifan%20Zhu-blue?logo=Google%20Scholar -->
<!-- https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fzhuyf8899%2Fzhuyf8899.github.io%40google-scholar-stats%2Fgs_data_shieldsio.json&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations -->
<!-- https://cdn.jsdelivr.net/gh/zhuyf8899/zhuyf8899.github.io@google-scholar-stats/gs_data_shieldsio.json -->

# 🔥 News
<span class='anchor' id='-news'></span>
- *2024.07*:&nbsp;🚀🚀CFPs: Our Special Issue [Multimodal Representation and Reasoning for Social Computing](https://www.ieeesmc.org/wp-content/uploads/2024/02/Multimodal-Representation-and-Reasoning-for-Social-Computing-CFP.pdf) in IEEE TCSS.
<!-- - *2024.05* : &nbsp; Congratulations to [Fanjin](https://zfjsail.github.io/) and [Haoran](https://lhrlab.github.io/) for our outstanding work (OAG-Bench and ChatKBQA) been accepted by KDD'24 and ACL'24! -->
<!-- - *2024.01* : &nbsp; I have been elected as an executive member of [CCF Data Governance Development Committee](https://www.ccf.org.cn/sjzlfzwyh/). -->
<!-- - *2023.12*: &nbsp; I have joined as an editorial board member of the [Information Fusion](https://www.sciencedirect.com/journal/information-fusion/about/editorial-board).  -->
<!-- - *2023.10*: &nbsp; We have organized a special issue entitiled "Applied Artificial Intelligence Approach: Intelligent Data Processing and Mining with Online Behaviors" on [Electronics](https://www.mdpi.com/journal/electronics/special_issues/D3L8Y3L5S7), and we warmly welcome submissions! -->
<!-- - *2023.09*: &nbsp; As an assistant professor, I joined in the School of Computer Science, Beijing University of Posts and Telecommunications, and worked closely with <a href='https://teacher.bupt.edu.cn/songmeina/zh_CN/index.htm'>Prof. Meina Song</a>,  <a href='https://teacher.bupt.edu.cn/ouzhonghong/zh_CN/index.htm'>Prof. Zhonghong Ou</a>, and  <a href='https://teacher.bupt.edu.cn/ehaihong/zh_CN/index.htm'>Prof. Haihong E</a>.  -->

# 📚 Publications 
<span class='anchor' id='-publications'></span>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

*: corresponding author,&nbsp;&nbsp;‡: co-first author

## Preprint

- Jingying Ma, ***Qika Lin***, Ziyu Jia, Mengling Feng, ***STUSleepNet: A SpatialTemporal Coupling Prominence Network for MultiChannel Sleep Staging***. [Paper](https://arxiv.org/pdf/2408.11884)
- ***Qika Lin***, Yifan Zhu, Xin Mei, Ling Huang, Jingying Ma, Kai He, Zhen Peng, Erik Cambria, Mengling Feng, ***Has Multimodal Learning Delivered Universal Intelligence in Healthcare? A Comprehensive Survey***. [Paper](https://arxiv.org/pdf/2408.12880)
- Fangzhi Xu‡, ***Qika Lin‡\****, Jiawei Han, Tianzhe Zhao, Jun Liu, Erik Cambria, ***Are Large Language Models Really Good Logical Reasoners? A Comprehensive Evaluation and Beyond***. [Paper](https://arxiv.org/pdf/2306.09841)
- Kai He, Rui Mao, ***Qika Lin***, Yucheng Ruan, Xiang Lan, Mengling Feng, Erik Cambria. ***A Survey of Large Language Models for Healthcare: from Data, Technology, and Applications to Accountability and Ethics***.[Paper](https://arxiv.org/pdf/2310.05694)



## 2024

- <mark style="background-color: #00008B"><span style="color:red">ACL 2024</span></mark> <mark style="background-color: #00008B"><font color= #F5F5F5>ACL 2024</font></mark> ``ACL 2024`` Fangzhi Xu, ***Qika Lin\****, Tianzhe Zhao, Jiawei Han, Jun Liu\*, ***PathReasoner: Modeling Reasoning Path with Equivalent Extension for Logical Question Answering***, 2024. [Paper](https://aclanthology.org/2024.acl-long.724/)
- ``ACL 2024`` Fangzhi Xu, Zhiyong Wu, Qiushi Sun, Siyu Ren, Fei Yuan, Shuai Yuan, ***Qika Lin***, Yu Qiao, Jun Liu,  ***SymbolLLM: Towards Foundational Symbolcentric Interface For Large Language Models***, 2024. [Paper](https://aclanthology.org/2024.acl-long.707/)
- ``IJCAI 2024`` Rui Mao, ***Qika Lin***, Qiawen Liu, Gianmarco Mengaldo, Erik Cambria, ***Understanding Public Perception Towards Weather Disasters Through the Lens of Metaphor***, 2024. [Paper](https://www.ijcai.org/proceedings/2024/818)
- ``SIGIR 2024`` Tianzhe Zhao, Jiaoyan Chen, Yanchi Ru, ***Qika Lin***, Yuxia Geng and Jun Liu, ***Untargeted Adversarial Attack on Knowledge Graph Embeddings***, 2024. [Paper](https://dl.acm.org/doi/10.1145/3626772.3657702)
- ``COLING 2024`` Jian Zhang, Changlin Yang, Haiping Zhu, ***Qika Lin***, Fangzhi Xu, Jun Liu, ***A Semantic Mention Graph Augmented Model for DocumentLevel Event Argument Extraction***, 2024. [Paper](https://aclanthology.org/2024.lrec-main.139/)
- ``ICDE 2024`` ***Qika Lin***, Jun Liu, Lingling Zhang, Yudai Pan, Xin Hu, Fangzhi Xu, Hongwei Zeng, ***Contrastive Graph Representations for Logical Formulas Embedding (Extended Abstract)***, TKDE Poster, 2024. [Paper](https://ieeexplore.ieee.org/document/10598103)
- ``ICDE 2024`` Yifan Zhu, ***Qika Lin***, Hao Lu, Kaize Shi, Donglei Liu, James Chambua, Shanshan Wan, Zhendong Niu, ***Recommending Learning Objects through Attentive HGC and OperationAware Neural Network (Extended Abstract)***, TKDE Poster, 2024. [Paper](https://ieeexplore.ieee.org/document/10598126)
- ``Cognitive Computation`` Hongcai Xu, Junpeng Bao, ***Qika Lin***, Lifang Hou, Feng Chen, ***Disentangling User Cognitive Intent with Causal Reasoning for Knowledge-Enhanced Recommendation***, Cognitive Computation, 2024. [Paper](https://link.springer.com/article/10.1007/s12559-024-10321-0)
- ``Information Fusion`` Yu Ma, Rui Mao, ***Qika Lin***, Peng Wu, Erik Cambria, ***Quantitative stock portfolio optimization by multi-task learning risk and return***, Information Fusion, 2024. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253523004815)
  
## 2023
- ``ACL 2023`` ***Qika Lin***, Jun Liu, Rui Mao, Fangzhi Xu, Erik Cambria, ***TECHS: Temporal Logical Graph Networks for Explainable Extrapolation Reasoning***, 2023. [Paper](https://aclanthology.org/2023.acl-long.71.pdf)
- ```IEEE TKDE``` ***Qika Lin***, Jun Liu, Lingling Zhang, Yudai Pan, Xin Hu, Fangzhi Xu, Hongwei Zeng, ***Contrastive Graph Representations for Logical Formulas Embedding***, 2023. [Paper](https://ieeexplore.ieee.org/document/9667296/)
- ```IEEE TKDE``` Yifan Zhu‡, ***Qika Lin‡***, Hao Lu, Kaize Shi, Donglei Liu, James Chambua, Shanshan Wan, and Zhendong Niu, ***Recommending Learning Objects through Attentive Heterogeneous Graph Convolution and Operation-Aware Neural Network***. IEEE Transactions on Knowledge and Data Engineering, 2023. [Paper](https://ieeexplore.ieee.org/abstract/document/9606527)
- ```Information Fusion``` ***Qika Lin***, Rui Mao, Jun Liu, Fangzhi Xu, Erik Cambria, ***Fusing Topology Contexts and Logical Rules in Language Models for Knowledge Graph Completion***, 2023. [Paper](https://linkinghub.elsevier.com/retrieve/pii/S1566253522001592)
- ``KDD 2023`` Yifan Zhu, Fangpeng Cong, Dan Zhang, Wenwen Gong, ***Qika Lin***, Wenzheng Feng, Yuxiao Dong, and Jie Tang, ***WinGNN: Dynamic Graph Neural Networks with Random Gradient Aggregation Window***, 2023. [Paper](https://dl.acm.org/doi/abs/10.1145/3580305.3599551) [Code](https://github.com/THUDM/WinGNN) 
- ```IEEE TKDE``` Lingling Zhang, Shaowei Wang, Jun Liu, Xiaojun Chang, ***Qika Lin***, Zongyuan Ge, Qinghua Zheng, ***MuL-GRN: Multi-Level Graph Relation Network for Few-Shot Node Classification***, 2023. [Paper](https://ieeexplore.ieee.org/document/9779997)
- ```IEEE TNNLS``` Fangzhi Xu, Jun Liu\*, ***Qika Lin\****, Tianzhe Zhao, Jian Zhang, Lingling Zhang, ***Mind Reasoning Manners: Enhancing Type Perception for Generalized Zeroshot Logical Reasoning over Text***, 2023. [Paper](https://ieeexplore.ieee.org/document/10267912)
- ```IEEE TNNLS``` Jie Ma, Jun Liu, ***Qika Lin***, Bei Wu, Yaxian Wang, Yang You, ***Multitask Learning for Visual Question Answering***, 2023. [Paper](https://ieeexplore.ieee.org/document/9525040)
- ```Information Fusion``` Yu Ma, Rui Mao, ***Qika Lin***, Peng Wu, Erik Cambria, ***Multi-source aggregated classification for stock price movement prediction***, 2023. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S1566253522002019?via%3Dihub)
- ```Pattern Recognition``` Fangzhi Xu, ***Qika Lin***, Jun Liu, Lingling Zhang, Tianzhe Zhao, Qi Chai, Yudai Pan, Yi Huang, Qianying Wang, ***MoCA: Incorporating domain pretraining and cross attention for textbook question answering***, 2023. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0031320323002893?via%3Dihub)
- ```IEEE TCSVT``` Yaxian Wang, Bifan Wei, Jun Liu, ***Qika Lin***, Lingling Zhang, ***Spatial-aware Multimodal Graph Network for Textbook Question Answering***, 2023. [Paper](https://ieeexplore.ieee.org/document/9996417)

## 2022
- ```SIGIR 2022``` ***Qika Lin***, Jun Liu, Fangzhi Xu, Yudai Pan, Yifan Zhu, Lingling Zhang, Tianzhe Zhao, ***Incorporating Context Graph with Logical Reasoning for Inductive Relation Prediction***, 2022. [Paper](https://dl.acm.org/doi/10.1145/3477495.3531996)
- ```SIGIR 2022``` Fangzhi Xu, Jun Liu, ***Qika Lin***, Yudai Pan and Lingling Zhang, ***Logiformer: A TwoBranch Graph Transformer Network for Interpretable Logical Reasoning***, 2022. [Paper](https://dl.acm.org/doi/10.1145/3477495.3532016)
- ```EMNLP 2022``` Yudai Pan, Jun Liu, Lingling Zhang, Tianzhe Zhao, ***Qika Lin***, Xin Hu, Qianying Wang, ***Inductive Relation Prediction with Logical Reasoning Using Contrastive Representations***, 2022. [Paper](https://aclanthology.org/2022.emnlp-main.286/)
- ```IEEE TIST``` Hao Lu, Yifan Zhu, ***Qika Lin***, Tan Wang, Zhendong Niu, Enrique HerreraViedma, ***Heterogeneous Knowledge Learning of Predictive Academic Intelligence in Transportation***, 2022. [Paper](https://ieeexplore.ieee.org/document/9298476)
  
## 2021 and before
- ```Information Sciences``` ***Qika Lin***, Jun Liu, Yudai Pan, Lingling Zhang, Xin Hu, Jie Ma, ***Rule-Enhanced Iterative Complementation for Knowledge Graph Reasoning***, 2021. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025521006319?via%3Dihub)
- ```FGCS``` ***Qika Lin‡***, Yifan Zhu‡, Hao Lu, Kaize Shi, Zhendong Niu, ***Improving University Faculty Evaluation via Multiview Knowledge Graph***, 2021. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0167739X20330454?via%3Dihub)
- ```KBS``` Yifan Zhu, ***Qika Lin***, Hao Lu, Kaize Shi, Ping Qiu, Zhendong Niu, ***Recommending Scientific Paper via Heterogeneous Knowledge Embedding based Attentive Recurrent Neural Networks***, 2021. [Paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705121000071?via%3Dihub)
- ```WSDM 2020``` Jie Ma, Jun Liu, Yufei Li, Xin Hu, Yudai Pan, Shen Sun, ***Qika Lin***, ***Jointly Optimized Neural Coreference Resolution with Mutual Attention***, 2020. [Paper](https://dl.acm.org/doi/10.1145/3336191.3371787)
- Yubing Nie, Yifan Zhu, ***Qika Lin***, Sifan Zhang, Pengfei Shi, Zhendong Niu, ***Academic rising star prediction via scholar’s evaluation model and machine learning techniques***. Scientometrics, 2019. [Paper](https://link.springer.com/article/10.1007/s11192-019-03131-x)
- ***Qika Lin***, Yifan Zhu, Sifan Zhang, Pengfei Shi, Qing Guo, Zhendong Niu, ***Lexical based automated teaching evaluation via students’ short reviews***. Computer Applications in Engineering Education, 2019. [Paper](https://onlinelibrary.wiley.com/doi/full/10.1002/cae.22068)

<!--
# 🎖 Honors and Awards
<span class='anchor' id='-honors-and-awards'></span>
-->
<!--
- *2023.10* Runner-up best paper award (ADS Track), ECML-PKDD 2023.
-->

# 🔍 Educations & Work Experiences

<span class='anchor' id='-educations'></span>

- *2023.09 - (now)*, Research Fellow at SSHSPH, National University of Singapore, Singapore. (Supervisor: [Prof. Mengling Feng](https://www.mornin-feng.com/) )
- *2021.10 - 2022.10*, Joint Ph.D. at CCDS, Nanyang Technological University, Singapore. (Supervisor: [Prof. Erik Cambria](https://scholar.google.com/citations?user=ilSYpW0AAAAJ))
- *2019.09 - 2023.06*, Ph.D. at School of Computer Science and Technology, Xi'an Jiaotong University, Shannxi, China. (Supervisor: [Prof. Jun Liu](https://gr.xjtu.edu.cn/web/liukeen))
- *2016.09 - 2019.06*, M.E. at School of Computer Science and Technology, Beijing Institute of Technology, Beijing, China. (Supervisor: [Prof. Zhendong Niu](https://cs.bit.edu.cn/szdw/jsml/js/nzd/index.htm))
- *2012.09 - 2019.06*, B.E. at School of Chemical Engineering and Environment, Beijing Institute of Technology, Beijing, China. 

# 🎤 Academic Services
<span class='anchor' id='-social'></span>

<!--
## Lectures

- *2024.06*, 推荐系统基础


## Invited Talks

- *2023.10*, 基础模型时代下隐私保护与可信数据要素流通, 第一届中国（成都）数智金融高峰论坛 [Slides](files/大模型时代下隐私保护与可信数据要素流通_数智论坛.pdf)
-->

## Editor Service

- *2024.07 - present*, ***Guest Editor (corresponding)*** of [IEEE Transactions on Computational Social Systems](https://www.ieeesmc.org/wp-content/uploads/2024/02/Multimodal-Representation-and-Reasoning-for-Social-Computing-CFP.pdf)
- *2023.10 - 2024.06*, ***Guest Editor*** of [Electronics](https://www.mdpi.com/journal/electronics/special_issues/D3L8Y3L5S7)

<!--
## Social Service

- Executive member of [CCF Expert Committee on Big Data](https://www.ccf.org.cn/Chapters/TC/TC_Listing/TFBD/)
- Executive member of [CCF Data Governance Development Committee](https://www.ccf.org.cn/sjzlfzwyh/)
-->

## Program Committee & Reviewer Service

- ***Program committee member*** of COLING'22-25, LOG'22-23, EMNLP'22-24, ACL'23-24, SIGIR'23-24, NeurIPS'24, ICLR'25, AISTATS'25, etc.
- ***Reviewer*** of TPAMI, IJCV, TKDE, TMC, TNNLS, TVSVT, TAI, TBD, TCSS, TKDD, TOSEM, KBS, Information Fusion, IEEE Intelligent Systems, etc.
- ***Special Session Chair*** [Knowledgedriven Graph Learning for Social Behavioral and Medical Data](https://besc-conf.org/2024/special-session-3), the International
Conference on Behavioural and Social Computing (BESC), 2024.

<!--
# Students
<span class='anchor' id='-students'></span>

### Class of 2024
- ***Master students***: Qingzhi Yu, Huiqiang Rong, Guanting Chen
- ***Undergraduate students***: Yihao Wang (visiting), Xinyu Mu (visiting)

### Class before 2023
- ***PhD students***: Yu Feng (Co-advised with Prof. Meina Song), Weibin Liao (Co-advised with Prof. Xuesong Li), Gen Shi (Co-advised with Prof. Xuesong Li)
-->
