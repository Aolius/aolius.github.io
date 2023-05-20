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

Hello, I am Ao Liu (刘傲， リュウ　アオ), a final-year Ph.D. student at Tokyo Institute of Technology.

My research interest includes natural language generation, semi-supervised learning and pretrained language models. 


# 🔥 News
- *2023.05*: &nbsp;🎉🎉 A paper accepted at *SEM 2023.
- *2022.12*: &nbsp;🎉🎉 A paper accepted at Journal of Information Processing.
- *2022.11*: &nbsp;🎉🎉 Finished my internship at IBM Research Tokyo. 
- *2022.10*: &nbsp;🎉🎉 A long paper accepted at EMNLP 2022.

# 📖 Educations
- *2020.09 - 2023.09*, doctoral student in the Department of Computer Science of Tokyo Institute of Technology, advised by Prof. Naoaki Okazaki.
- *2017.09 - 2020.06*, master student in the School of Computer Science and Engineering of UESTC, advised by Prof. Zenglin Xu.
- *2013.09 - 2017.06*, undergraduate student in the School of Information and Communication Engineering of University of Electronic Science and Technology of China (UESTC), advised by Prof. Zenglin Xu.
- *2015.09 - 2016.08*, exchange student in the JUSST program of the University of Electro-Communications, advised by Prof. Hisashi Koga.

# 💼 Internships
- *2022.08 - 2022.11*, IBM Research Tokyo, advised by Yang Zhao.
- *2021.11 - 2022.06*, Microsoft Research Asia, advised by Haoyu Dong.

# 📝 Preprints
-  Towards Effective Multi-Task Interaction for Entity-Relation Extraction: A Unified Framework with Selection Recurrent Network. [\[paper\]](https://arxiv.org/abs/2202.07281). An Wang, **Ao Liu**, Hieu Hanh Le and Haruo Yokota.

# 📝 Publications
- Generative Data Augmentation for Aspect Sentiment Quad Prediction. An Wang, Junfeng Jiang, Youmi Ma, **Ao Liu**, and Naoaki Okazaki.  In Proceedings of *SEM 2023: The 12th Joint Conference on Lexical and Computational Semantics (StarSEM), pages (to appear), Toronto, Canada, July 2023.
- Improving Logical-level Natural Language Generation with Topic-conditioned Data Augmentation and Logical Form Generation. [\[paper\]](https://www.jstage.jst.go.jp/article/ipsjjip/31/0/31_332/_article/-char/ja/). **Ao Liu**, Congjian Luo, Naoaki Okazaki. Journal of Information Processing, May 2023.
- PLOG: Table-to-Logic Pretraining for Logical Table-to-Text Generation. [\[paper\]](https://arxiv.org/abs/2205.12697); [\[code\]](https://github.com/microsoft/PLOG). **Ao Liu**, Haoyu Dong, Naoaki Okazaki, Shi Han, Dongmei Zhang. Proceedings of the 2022 Conference on Empirical Methods in Natural Language Processing (**EMNLP 2022**).
- Exploiting Unlabeled Data for Target-Oriented Opinion Words Extraction. [\[paper\]](https://arxiv.org/abs/2208.08280); [\[code\]](https://github.com/TOWESSL/TOWESSL). Yidong Wang, Hao Wu, **Ao Liu**, Wenxin Hou, Zhen Wu, Jindong Wang, Takahiro Shinozaki, Manabu Okumura, Yue Zhang. International Conference on Computational Linguistics 2022 (**COLING 2022**).
- A Unified Weight Initialization Paradigm for Tensorial Convolutional Neural Networks. [\[paper\]](https://arxiv.org/abs/2205.15307). Yu Pan, Zeyong Su, **Ao Liu**, Wang J Q, Nannan Li, Zenglin Xu. Thirty-ninth International Conference on Machine Learning (**ICML 2022**).
- Table Pretraining: A Survey on Model Architectures, Pretraining Objectives, and Downstream Tasks. [\[paper\]](https://arxiv.org/abs/2201.09745). Haoyu Dong, Zhoujun Cheng, Xinyi He, Mengyu Zhou, Anda Zhou, Fan Zhou, **Ao Liu**, Shi Han and Dongmei Zhang. The 31st International Joint Conference on Artificial Intelligence. (**IJCAI-ECAI 2022**, Survey Track).
- Semi-Supervised Formality Style Transfer with Consistency Training [\[paper\]](https://arxiv.org/abs/2203.13620); [\[code\]](https://github.com/aolius/semi-fst). **Ao Liu**, An Wang, Naoaki Okazaki. Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (**ACL 2022**).
- Multi-Level Multimodal Transformer Network for Multi-Modal Recipe Comprehension. [\[paper\]](https://drive.google.com/file/d/1hd1tbhhGdXI3WWEF9rfrt64mYEtKb_x5/view). **Ao Liu**, Shuai Yuan, Chenbin Zhang, Congjian Luo, Yaqing Liao, Zenglin Xu. Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (short) (**SIGIR 2020**).
- Improving Contextual Language Models for Response Retrieval in Multi-Turn Conversation. [\[paper\]](https://www.researchgate.net/profile/Junyu-Lu-8/publication/343213861_Improving_Contextual_Language_Models_for_Response_Retrieval_in_Multi-Turn_Conversation/links/60054100299bf14088a2efb6/Improving-Contextual-Language-Models-for-Response-Retrieval-in-Multi-Turn-Conversation.pdf). Junyu Lu, Xiancong Ren, Yazhou Ren, **Ao Liu**, Zenglin Xu. Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (short) (**SIGIR 2020**).
- Read, Attend, and Exclude: Multi-Choice Reading Comprehension by Mimicking Human Reasoning Process. [\[paper\]](https://drive.google.com/file/d/1r8PqEd6gKvTYfQOfK2zGuDx0lBGLvxbY/view). Chenbin Zhang, Congjian Luo, Junyu Lu, **Ao Liu**, Bing Bai, Kun Bai and Zenglin Xu. Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval (short) (**SIGIR 2020**).
- Machine Reading Comprehension: Matching and Orders. [\[paper\]](https://drive.google.com/file/d/1GCs-YB55vBk9KniWSWjyd-7B6GtD-fWG/view); [\[code\]](https://github.com/Aolius/OrdMatch). **Ao Liu**, Lizhen Qu, Junyu Lu, Chenbin Zhang, Zenglin Xu. Proceedings of the 28th ACM International Conference on Information and Knowledge Management (short) (**CIKM 2019**).



# 🎖 Honors and Awards

- Stars of Tomorrow, Microsoft Research Asia, 2022.
- Tokyo Tech Advanced Human Resource Development Fellowship for Doctoral Students, Tokyo Institute of Technology, 2021-2023 (Scholarship 1,800,000 JPY/year, Research Funds 300,000 JPY/year)
- Tsubame Scholarship, Tokyo Institue of Technology, 2020.
- SIGIR Student Travel Grants: SIGIR2020, CIKM2019.

# 💬 Invited Talks
- *2022.08*, *Table-to-Logic Pretraining for Logical Table-to-Text Generation.* Invited talk at Knowledge and Information Research Team，National Institute of Advanced Industrial Science and Technology (AIST).

# 📄 Academic Services
- Reviewer for Conferences: ICML (2022, 2023), NeurIPS 2022, EMNLP 2022, ACL 2023.
