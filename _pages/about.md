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

Hi! I'm Yifei Huang (黄逸飞). I received my PhD and M.S. from the Graduate School of Information Science and Technology at the [University of Tokyo](http://www.u-tokyo.ac.jp/en/), supervised by Prof. Yoichi Sato, under the support of the [Global Creative Leader](http://www.gcl.i.u-tokyo.ac.jp/) program of the University of Tokyo. I received my B.S. in Automation in [IEEE honor class](http://english.seiee.sjtu.edu.cn/english/info/8338.htm) of [Shanghai Jiao Tong University](http://en.sjtu.edu.cn/). I am currently a Project Assistant Professor (特任助教) in [Sato Laboratory](http://www.hci.iis.u-tokyo.ac.jp/), the [University of Tokyo](http://www.u-tokyo.ac.jp/en/). I am fortunate to have worked with esteemed researchers like [Prof. Yoichi Sato](http://www.hci.iis.u-tokyo.ac.jp/~ysato/index.html), Prof. [Yusuke Sugano](https://www.yusuke-sugano.info/), Prof. [Yu Qiao](https://mmlab.siat.ac.cn/yuqiao), Prof. [Kris Kitani](https://kriskitani.github.io/), Prof. [Kai Kunze](https://kaikunze.de/), and Prof. [Weidi Xie](https://weidixie.github.io/). I focus on exciting topics in video understanding, egocentric vision, and their applications. 



# 🗞️ Academic Services
- Area Chair: ICCV 2023, CVPR 2024.
- Reviewer: T-PAMI, IJCV, CVPR, ICCV, ECCV, ACCV, ICML, NeurIPS, AAAI, TCSVT, ICRA, IWMUT, etc.

# 💻 Researches
I have published 20+ papers at the top international AI conferences with 1000+ <a href='https://scholar.google.com/citations?user=RU8gNcgAAAAJ'> Google Scholar </a> citations. My primary research interests lie in:

- First-person (egocentric) videos, egocentric gaze, and gaze-guided interaction systems.

- Egocentric video understanding, action recognition/segmentation/anticipation, vision-language understanding.

- Video understanding from limited labels, few-shot learning, domain adaptation.

Please feel free to contact me by email for any suggestions, questions, or potential collaborations.

# 📝 Publications 
(* denotes corresponding author)
### 📒 Topic:  First-person (egocentric) Videos, Egocentric Gaze, and Gaze-guided Interaction Systems
1. [Predicting gaze in egocentric videos by learning task-dependent attention transition](https://cai-mj.github.io/files/HCLS_eccv_arxiv2018.pdf)  \|  [[Project](https://cai-mj.github.io/project/egocentric_gaze_prediction)]  \| [[Code & Data](https://github.com/hyf015/egocentric-gaze-prediction)]  \| [[BibTex](/docs/eccv2018.txt)]               
**Y. Huang**, M. Cai, Z. Li, and Y. Sato. (<font color="blue">oral presentation, acceptance rate: 2%</font>)               
**ECCV 2018**               

1. [Mutual Context Network for Jointly Estimating Egocentric Gaze and Actions](https://arxiv.org/pdf/1901.01874) \|  [[Project & Code](https://cai-mj.github.io/project/egocentric_gaze_prediction)]  \| [[BibTex](/docs/tip2020.txt)]               
**Y. Huang**, M. Cai, Z. Li, F. Lu, and Y. Sato.               
**IEEE TIP 2020**

1. [An Ego-Vision System for Discovering Human Joint Attention](https://drive.google.com/file/d/1F7GdOfMJNEzf8c3RcZNxo-VevN-3vMiJ/view) \|  [[Project & Code](https://cai-mj.github.io/project/egocentric_gaze_prediction)]  \| [[BibTex](/docs/thms2020.txt)]               
**Y. Huang**, M. Cai, and Y. Sato.               
**IEEE THMS 2020**               

1. [Leveraging Human Selective Attention for Medical Image Analysis with Limited Training Data](https://arxiv.org/pdf/2112.01034) \| [[BibTex](/docs/bmvc2021-1.txt)]               
**Y. Huang**, X. Li, L. Yang, L. Gu, Y. Zhu, H. Seo, Q. Meng, T. Harada, and Y. Sato.               
**BMVC 2021**

1. [Goal-Oriented Gaze Estimation for Zero-Shot Learning](http://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Goal-Oriented_Gaze_Estimation_for_Zero-Shot_Learning_CVPR_2021_paper.pdf) \| [[BibTex](/docs/cvpr2021.txt)]               
Y.Liu, L.Zhou, X.Bai, **Y. Huang**, L. Gu, J. Zhou and T. Harada.
**CVPR 2021**

1. [GazeSync: Eye Movement Transfer Using an Optical Eye Tracker and Monochrome Liquid Crystal Displays](https://research.gold.ac.uk/id/eprint/33046/1/Seeing%20our%20Blind%20Spots-%20Smart%20Glasses-based%20Simulation%20to%20Increase%20Design%20Students%E2%80%99%20Awareness%20of%20Visual%20Impairment%20Zhang%20UIST2022.pdf) \| [[BibTex](/docs/iui2022.txt)]               
Q. Zhang, **Y. Huang**, G. Chernyshov, J. Li, YS. Pai, and K. Kunze.               
**IUI 2022**

1. [Seeing our Blind Spots: Smart Glasses-based Simulation to Increase Design Students' Awareness of Visual Impairment](https://www.researchgate.net/profile/Qing-Zhang-103/publication/359398906_GazeSync_Eye_Movement_Transfer_Using_an_Optical_Eye_Tracker_and_Monochrome_Liquid_Crystal_Displays/links/6239e7e33cf0f2118f4d1f3c/GazeSync-Eye-Movement-Transfer-Using-an-Optical-Eye-Tracker-and-Monochrome-Liquid-Crystal-Displays.pdf) \| [[BibTex](/docs/uist2022.txt)]               
Q. Zhang, G. Barbareschi, **Y. Huang**, J. Li, YS. Pai, J. Ward and K. Kunze.               
**UIST 2022**               

### 📒 Topic:  General Video Understanding, Video Understanding with Limited Labels.
1. [Matching Compound Prototypes for Few-Shot Action Recognition]() \| [[Code](https://drive.google.com/file/d/1brIAthibvoc86evIQUa01CULQZ7Ko8Z5/view?usp=sharing)] \| [[BibTex](/docs/ijcv2024.txt)]               
**Y. Huang**, L. Yang, G. Chen, H. Zhang, F. Lu, and Y. Sato.               
**IJCV 2024**

1. [Weakly Supervised Temporal Sentence Grounding With Uncertainty-Guided Self-Training](http://openaccess.thecvf.com/content/CVPR2023/papers/Huang_Weakly_Supervised_Temporal_Sentence_Grounding_With_Uncertainty-Guided_Self-Training_CVPR_2023_paper.pdf) \| [[Code](https://drive.google.com/drive/folders/1na35rpEgLYE6fet6SM3N-ZSoyYDs11To?usp=sharing)] \| [[BibTex](/docs/cvpr2023.txt)]               
**Y. Huang**, L. Yang, and Y. Sato.               
**CVPR 2023**

1. [Compound Prototype Matching for Few-Shot Action Recognition](https://arxiv.org/pdf/2207.05515) \| [[Code](https://drive.google.com/file/d/1brIAthibvoc86evIQUa01CULQZ7Ko8Z5/view?usp=sharing)] \| [[BibTex](/docs/eccv2022.txt)]               
**Y. Huang**, L. Yang, and Y. Sato.               
**ECCV 2022**

1. [Improving Action Segmentation via Graph-based Temporal Reasoning](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_Improving_Action_Segmentation_via_Graph-Based_Temporal_Reasoning_CVPR_2020_paper.pdf) \| [[Code](https://drive.google.com/file/d/1Bc02QyoWzPNAd1djswCoYxxAHBjITrQ3/view?usp=sharing)] \| [[BibTex](/docs/cvpr2020.txt)]               
**Y. Huang**, Y. Sugano and Y. Sato.               
**CVPR 2020**

1. [Interact before Align: Leveraging Cross-Modal Knowledge for Domain Adaptive Action Recognition](https://openaccess.thecvf.com/content/CVPR2022/papers/Yang_Interact_Before_Align_Leveraging_Cross-Modal_Knowledge_for_Domain_Adaptive_Action_CVPR_2022_paper.pdf) \| [[BibTex](/docs/cvpr2022.txt)]               
L. Yang, **Y. Huang<span>&#42;</span>**, Y. Sugano and Y. Sato.               
**CVPR 2022**

1. [Retrieval-augmented Egocentric Video Captioning](https://arxiv.org/pdf/2401.00789) \| [[BibTex](/docs/cvpr2024-x.txt)] \| [[Project&Code]](https://jazzcharles.github.io/Egoinstructor/)              
J. Xu, **Y. Huang**, J. Hou, G. Chen, Y. Zhang, R. Feng, and W. Xie.            
**CVPR 2024**



### 📒 Topic:  Egocentric Video Benchmarks.
1. [EgoExoLearn: A Dataset for Bridging Asynchronous Ego- and Exo-centric View of Procedural Activities in Real World](https://arxiv.org/abs/2403.16182) \| [[Project&Code](https://github.com/OpenGVLab/EgoExoLearn)] \| [[BibTex](/docs/cvpr2024-h/txt)]               
**Y. Huang**, G. Chen, J. Xu, ... , Y. Qiao          
**CVPR 2024** 

1. [Ego4D: Around the World in 3,000 Hours of Egocentric Video](https://arxiv.org/pdf/2112.01038) \| [[Project](https://ego4d-data.org/)] \| [[BibTex](/docs/ego4d.txt)]               
K. Grauman, A. Westbury, ..., **Y. Huang**, ..., J. Malik.            
**CVPR 2022** (<font color="blue">Best paper finalist.</font>)

1. [Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives](https://arxiv.org/pdf/2311.18259) \| [[Project](https://ego-exo4d-data.org/)] \| [[BibTex](/docs/egoexo4d.txt)]               
K. Grauman, A. Westbury, ..., **Y. Huang**, ..., J. Malik.         
**CVPR 2024** (<font color="blue">oral presentation</font>) 





# 🔥 News
- 3 Papers accepted by ECCV 2024, in which [ActionVOS](https://arxiv.org/pdf/2407.07402) got accepted as oral!
- 3 Papers accepted by CVPR 2024.
- Served as an Area Chair for ICCV 2023 and CVPR 2024.
- Received Special Grant for Foreign Researchers (¥11,000,000) from [JSPS](https://www.jsps.go.jp/index.html).
- Received Grant-in-Aid for Early-Career Scientists (¥4,550,000) from [JSPS](https://www.jsps.go.jp/index.html).
