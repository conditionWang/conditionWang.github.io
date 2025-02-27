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

This is Lixu Wang. I am now visiting Nanyang Technological University (NTU) and working with [Prof. Wei Dong](https://weidong.hk/) and [Prof. Xiaofeng Wang](https://homes.luddy.indiana.edu/xw7/) from Indiana University. I am a Ph.D. candidate in Computer Science at Northwestern University (NU), advised by [Prof. Qi Zhu](https://scholar.google.com/citations?user=TN09YMcAAAAJ&hl=en) and [Prof. Xiao Wang](https://wangxiao1254.github.io/), and partially supported by [IBM PhD Fellowship](https://research.ibm.com/university/awards/fellowships-awardees.html). Prior to Northwestern, I obtained my B.E. from Zhejiang University (ZJU) in July 2020 under the supervision of [Prof. Wenyuan Xu](https://scholar.google.com/citations?hl=en&user=FCsdj0YAAAAJ&view_op=list_works). I am open to all kinds of collaboration, please email me if you are interested in my research.

I aim to contribute to Data-Centric Responsible AI, where my current interest is to achieve Controllable Customization for Large Models. In this topic, I focus on the content and user control of large foundation models, i.e., 1) what content should be included in models; 2) what content should be excluded from models; and 3) who should be authorized to use the models. Solving these problems benefits major facets of responsible AI, like ensuring data and model privacy protection, enhancing model reliability and accountability, aligning for benign purposes, and preventing harmful misuse. To achieve these goals, I have been developing novel techniques and approaches related to Federated Learning, Out-Source Training, Machine Unlearning, Generalization Restriction, and Multi-Party Computation with a diverse set of knowledge in Optimization Theory, Information Theory, and Cryptography.



# 🔥 News
- *2025.02*: &nbsp; 🎉Our paper about private downstream task adaptation of pre-trained transformers has been accepted to **CVPR 2025**.
- *2025.01*: &nbsp; One paper about time-series analysis has been submitted to TMLR 2025.
- *2025.01*: &nbsp; 🎉Our papers about LLM unlearning and backdoor attacks have been accepted by **ICLR 2025**.
- *2025.01*: &nbsp; Papers about multimodal LLM privacy and FL have been submitted to Usenix Security 2025 and ICML 2025.
- *2024.12*: &nbsp; One paper about object detection in edge computing has been submitted to TMC.
- *2024.09*: &nbsp; 🎉Our paper about Image Retrieval has been accepted by **NeurIPS 2024**.
- *2024.03*: &nbsp; Help to submit one NSF proposal with CISPA.
- *2023.12*: &nbsp; 🎉Our paper about anomaly detection has been accepted by **ICASSP 2024**.
- *2023.09*: &nbsp; 🎉Our paper about data IP has been accepted by **NeurIPS 2023**.
- *2023.08*: &nbsp; 🎉Super excited to be an **IBM PhD Fellowship** recipient.
- *2023.07*: &nbsp; 🎉Our paper about backdoor detection has been accepted by **ICCV 2023**.
- *2023.04*: &nbsp; 🎉Help submit two **NSF proposals** accepted later.
- *2023.01*: &nbsp; 🎉Our paper about domain generalization has been accepted by **ICLR 2023**.
- *2022.11*: &nbsp; Become a visiting research scientist at General Motors.
- *2022.03*: &nbsp; 🎉Our paper about incremental learning is accepted by **CVPR 2022**.
- *2022.02*: &nbsp; 🎉Our paper about incremental learning is accepted by **TNNLS 2021**.
- *2022.01*: &nbsp; 🎉Our paper about model IP is accepted by **ICLR 2022** as an **oral** presentation.
- *2021.07*: &nbsp; 🎉Our paper about domain adaptation is accepted by **ICCV 2021**.
- *2021.03*: &nbsp; 🎉Our paper about digital watermarks is accepted by **USENIX Security 2021**.
- *2020.12*: &nbsp; 🎉Our paper about federated learning is accepted by **AAAI 2021**.
- *2020.07*: &nbsp; 🎉Received **Outstanding Undergraduate Dissertation** Award of ZJU.


# 📝 Publications 
\* denotes equal contribution, # denotes corresponding authors

## Preprint
- [**Phase-driven Generalization for Nonstationary Time Series**](https://arxiv.org/abs/2402.05960)
  - Payal Mohapatra\*, **Lixu Wang**\*, Qi Zhu
  - Arxiv 2024
- [**Federated Continual Novel Class Learning**](https://arxiv.org/abs/2312.13500)
  - **Lixu Wang**\*, Chenxi Liu\*, Junfeng Guo, Jiahua Dong, Xiao Wang, Heng Huang, Qi Zhu
  - Arxiv 2023
- [**Federated Learning with New Knowledge: Fundamentals, Advances, and Futures**](https://arxiv.org/abs/2402.02268)
  - **Lixu Wang**, Yang Zhao, Jiahua Dong, Ating Yin, Qinbin Li, Xiao Wang, Dusit Niyato, Qi Zhu
  - Arxiv 2024
- [**Eavesdrop the Composition Proportion of Training Labels in Federated Learning**](https://arxiv.org/abs/1910.06044)
  - **Lixu Wang**, Shichao Xu, Xiao Wang, Qi Zhu
  - Arxiv 2019

 
## Peer-reviewed Conferences
- [_**Split Adaptation for Pre-trained Vision Transformers**_](https://arxiv.org/abs/2407.10223)
  - **Lixu Wang**\*, Bingqi Shang\*, Yi Li, Payal Mohapatra, Wei Dong, Xiao Wang, Qi Zhu
  - IEEE/CVF Conference on Computer Vision and Pattern Recognition, **CVPR 2025**
- [_**On Large Language Model Continual Unlearning**_](https://arxiv.org/abs/2407.10223)
  - **Lixu Wang**\* #, Chongyang Gao\*, Kaize Ding, Chenkai Weng, Xiao Wang, Qi Zhu
  - International Conference on Learning Representation, **ICLR 2025**
- [_**Semantic Feature Learning for Universal Unsupervised Cross-Domain Retrieval**_](https://arxiv.org/abs/2403.05690)
  - **Lixu Wang**, Xinyu Du, Qi Zhu
  - 38th Conference on Neural Information Processing Systems, **NeurIPS 2024**
- [_**DACR: Distribution-Augmented Contrastive Reconstruction for Time-Series Anomaly Detection**_](https://ieeexplore.ieee.org/abstract/document/10447891/)
  - **Lixu Wang**, Shichao Xu, Xinyu Du, Qi Zhu
  - International Conference on Acoustics, Speech, and Signal Processing, **ICASSP 2024**
- [_**Deja Vu: Continual Model Generalization for Unseen Domains**_](https://openreview.net/forum?id=L8iZdgeKmI6)
  - **Lixu Wang**\* #, Chenxi Liu\*, Linjun Lu, Chen Sun, Xiao Wang, Qi Zhu
  - International Conference on Learning Representation, **ICLR 2023**
- [_**Federated Class-Incremental Learning**_](https://openaccess.thecvf.com/content/CVPR2022/html/Dong_Federated_Class-Incremental_Learning_CVPR_2022_paper.html)
  - **Lixu Wang**\*, Jiahua Dong\*, Zhen Fang, Gan Sun, Shichao Xu, Xiao Wang, Qi Zhu
  - IEEE/CVF Conference on Computer Vision and Pattern Recognition, **CVPR 2022**
- [_**Non-Transferable Learning: A New Approach for Model Ownership Verification and Applicability Authorization**_](https://openreview.net/forum?id=tYRrOdSnVUy)
  - **Lixu Wang**\*, Shichao Xu\*, Ruiqi Xu, Xiao Wang, Qi Zhu
  - International Conference on Learning Representation, **ICLR 2022 Oral**
- [_**Weak Adaptation Learning: Addressing Cross-domain Data Insufficiency with Weak Annotator**_](https://openaccess.thecvf.com/content/ICCV2021/html/Xu_Weak_Adaptation_Learning_Addressing_Cross-Domain_Data_Insufficiency_With_Weak_Annotator_ICCV_2021_paper.html)
  - Shichao Xu\*, **Lixu Wang**\*, Yixuan Wang, Qi Zhu
  - IEEE/CVF Conference on Computer Vision, **ICCV 2021**
- [_**Addressing Class Imbalance in Federated Learning**_](https://ojs.aaai.org/index.php/AAAI/article/view/17219)
  - **Lixu Wang**, Shichao Xu, Xiao Wang, Qi Zhu
  - AAAI Conference on Artificial Intelligence, **AAAI 2021**
- [**Can We Trust Embodied Agents? Exploring Backdoor Attacks against Embodied LLM-Based Decision-Making Systems**](https://arxiv.org/abs/2405.20774)
  - Ruochen Jiao, Shaoyuan Xie, Justin Yue, Takami Sato, **Lixu Wang**, Yixuan Wang, Qi Alfred Chen, Qi Zhu
  - International Conference on Learning Representation, **ICLR 2025**
- [_**PolicyCleanse: Backdoor Detection and Mitigation for Competitive Reinforcement Learning**_](https://openaccess.thecvf.com/content/ICCV2023/html/Guo_PolicyCleanse_Backdoor_Detection_and_Mitigation_for_Competitive_Reinforcement_Learning_ICCV_2023_paper.html)
  - Junfeng Guo, Ang Li, **Lixu Wang**, Cong Liu
  - IEEE/CVF Conference on Computer Vision, **ICCV 2023**
- [_**Domain Watermark: Effective and Harmless Dataset Copyright Protection is Closed at Hand**_](https://proceedings.neurips.cc/paper_files/paper/2023/hash/aa6287ca31ae1474ea802342d0c8ba63-Abstract-Conference.html)
  - Junfeng Guo, Yiming Li, **Lixu Wang**, Shu-Tao Xia, Heng Huang, Cong Liu, Bo Li
  - 37th Conference on Neural Information Processing Systems, **NeurIPS 2023**
- [_**mID: Tracing Screen Photos via Moire Patterns**_](https://www.usenix.org/conference/usenixsecurity21/presentation/cheng-yushi)
  - Yushi Cheng, Xiaoyu Ji, **Lixu Wang**\*, Qi Pang\*, Yi-Chao Chen, Wenyuan Xu
  - USENIX Security Symposium, **Usenix Security 2021**

## Peer-reviewed Journals

- [_**A Survey of Federated Unlearning: A Taxonomy, Challenges, and Future Directions**_](https://arxiv.org/abs/2310.19218)
  - Jiaxi Yang, Yang Zhao, Yiling Tao, **Lixu Wang**, Xiaoxiao Li, Dusit Niyato
  - IEEE **Network Magazine 2024**
- [_**Incremental 3D Object Recognition for Point Cloud Representation**_](https://ieeexplore.ieee.org/abstract/document/10054469)
  - Jiahua Dong, Gan Sun, **Lixu Wang**, Jun Li, Lingjuan Lyu, Konukoglu Ender
  - IEEE Transaction on Neural Networks and Learning Systems, **TNNLS 2022**



# 🎖 Honors and Awards
- *2023 - 2024*: [IBM Ph.D. Fellowship](https://research.ibm.com/university/awards/fellowships-awardees.html)
- *2020*: Outstanding Undergraduate Dissertation Award (ZJU)
- *2020*: Computer Science Ph.D. Fellowship (NU)
- *2020*: Outstanding Graduate of Zhejiang (Zhejiang Provincial Government)
- *2019*: _Wang Guosong_ Outstanding Scholarship (ZJU highest honor in EECS)
- *2018*: _1st Prize_, Chinese Mathematical Contest in Modeling, top 0.3%

# 📖 Educations
- *2021.01 - Present*, Northwestern University, Ph.D. in Computer Science, GPA: 4.0/4.0
- *2016.09 - 2020.07*, Zhejiang University, B.E. in Electrical and Computer Engineering, GPA: 3.96/4.0

# 💬 Invited Talks
- *2022.07*, Contrastive Learning for Time-Series Anomaly Detection, General Motors invited talks. 
- *2022.06*, Machine Learning with Constraints from Generalization, ZJU invited talks, Hangzhou.
- *2022.05*, Non-Transferable Learning for Model IP Protection, Sony AI Journal Club.
- *2022.03*, Federated Class-Incremental Learning, SSFAI Academic Invited Talks.

# 💻 Services
- *Reviewer/Program Committee*: NeurIPS, ICLR, ICML, CVPR, ICCV, ECCV, AAAI, MM, WACV, TNNLS, TCSVT, etc.
- *Advising*: Ruiqi Xu (B.S. NU &rarr; Ph.D. Uchicago); Chenxi Liu (M.S. NU &rarr; Ph.D. UMaryland), Jinjin Cai (M.S. NU &rarr; Ph.D. Purdue), Yufei Wang (M.S. NU &rarr; Ph.D. Northeastern), Shiyuan Duan (M.S. NU &rarr; Ph.D. UIUC), Bingqi Shang (M.S. NU &rarr; Ph.D. MSU).
