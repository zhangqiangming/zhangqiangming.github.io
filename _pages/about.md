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

# 👨‍🎓 About Me

#### I am a Ph.D. Candidate in Computer Architecture at Huazhong University of Science and Technology (HUST), located in Wuhan. My doctoral research is under the supervision of Prof. [Yuchong Hu](), and I am also affiliated with the research group led by Prof. [Dan Feng](). I expect to graduate in May 2026.



#### Previously, I received my MS degree from Sichuan University in 2022. As of now, I have contributed to more than 12 research papers (6 of which I authored as the first or corresponding author), such as ICDE2026, HPDC2025, HPDC2024, CADCG2021, and ICV2022.
<!-- <a href=''><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->


<!-- with publications or acceptances in prominent conferences and journals within the computer science field, -->
<!-- <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>) -->


# ⌛	 Research Interests
- Computer Architecture
- High-Performance Distributed Training and Inference
- Storage for AI (Storage4AI), Systems for AI (System4AI)
- Large Language Model (LLM) Systems and Storage
- Computer Vision, Person Re-Identification

 
<!-- 🔥 -->
# 🔥 News
- *2025.10*: &nbsp;🌻🎉 Our paper [SSFusion]() has been accepted to ICDE2026 (The 42st IEEE International Conference on Data
Engineering ). I am the first author of this work.
- *2025.07*: &nbsp;🌻🎉 I was awarded the HPDC2025 International Conference Travel Award (1,600 USD).
- *2025.04*: &nbsp;🌻🎉 Our paper [ResiReduce]() has been accepted to Euro-Par2025 (The 31st International European Conference on Parallel and Distributed Computing). I contributed as the second author.
- *2025.03*: &nbsp;🌻🎉 Our paper [SAFusion]() has been accepted to HPDC2025 (The 34th ACM International Symposium on High-Performance Parallel and Distributed Computing). I am the first author of this work.
- *2024.12*: &nbsp;🌻🎉 Our project won the First Prize in the 2nd National Information Storage Competition.
- *2024.06*: &nbsp;🌻🎉 I was awarded the HPDC2024 International Conference Travel Award (850 USD). 
- *2024.04*: &nbsp;🌻🎉 Our paper [ADTopk]() has been accepted to HPDC2024 (The 33rd International Symposium on High-Performance Parallel and Distributed Computing). I am the first author of this work. 




# 📝 Publications 

-	__<u>Zhangqiang Ming</u>__, Rui, Wang, Yuchong Hu, Yuanhao Shu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "SSFusion: Tensor Fusion with Selective Sparsification for Efficient Distributed DNN Training." 2026. In Proceedings of the 42st IEEE International Conference on Data Engineering (__ICDE'26__, CCF-A, CSRanking) [[Code]](https://github.com/zqming-cs) [[Preview]](https://zhangqiangming.github.io/papers/1_ICDE2026_.pdf)[[Download]](https://zhangqiangming.github.io/papers/1_ICDE2026_.pdf)


-	__<u>Zhangqiang Ming</u>__, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "SAFusion: Efficient Tensor Fusion with Sparsification Ahead for High-Performance Distributed DNN Training." 2025. In Proceedings of the 34th ACM International Symposium on High-Performance Parallel and Distributed Computing. (__HPDC'25__, Acceptance Rate=18.7%, CCF-B, CSRanking) [[Code]](https://github.com/zqming-cs) [[Preview]](https://zhangqiangming.github.io/papers/2_HPDC2025_.pdf)[[Download]](https://zhangqiangming.github.io/papers/2_HPDC2025_.pdf)


-	__<u>Zhangqiang Ming</u>__, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "ADTopk: All-Dimension Top-k Compression for High-Performance Data-Parallel DNN Training." 2024. In Proceedings of the 33rd International Symposium on High-Performance Parallel and Distributed Computing. (__HPDC'24__, Acceptance Rate=17.1%, CCF-B, CSRanking) [[Code]](https://github.com/zqming-cs) [[Preview]](https://zhangqiangming.github.io/papers/3_HPDC2024_.pdf)[[Download]](https://zhangqiangming.github.io/papers/3_HPDC2024_.pdf)





-	__<u>Zhangqiang Ming</u>__, Min Zhu, Xiangkun Wang, Jiamin Zhu, Junlong Cheng, Chengrui Gao, Yong Yang, and Xiaoyong Wei. "Deep learning-based person re-identification methods: A survey and outlook of recent works." Image and Vision Computing 119 (2022): 104394. (__ICV22__, CCF-C; IF:3.291) [[Preview]](https://zhangqiangming.github.io/papers/4_IVC2022_.pdf)[[Download]](https://zhangqiangming.github.io/papers/4_IVC2022_.pdf)



-	__<u>Zhangqiang Ming</u>__, Min Zhu, Jianrong Yan, Yong Yang, and Jiamin Zhu. "A survey on generative adversarial network based person re-identification method." Journal of Computer-Aided Design & Computer Graphics 34, no. 2 (2022): 163-179. (__CADCG21__, CCF-A) [[Preview]](https://zhangqiangming.github.io/papers/5_CADCG2021_.pdf)[[Download]](https://zhangqiangming.github.io/papers/5_CADCG2021_.pdf)


-	__<u>Zhangqiang Ming</u>__, Yong Yang, Xiaoyong Wei, Jianrong Yan, Xiangkun Wang, Fengjie Wang, and Min Zhu. "Global-local dynamic feature alignment network for person re-identification." arXiv preprint arXiv:2109.05759 (2021). [[Preview]](https://zhangqiangming.github.io/papers/6_ReID_.pdf)[[Download]](https://zhangqiangming.github.io/papers/6_ReID_.pdf)


-	__<u>Zhangqiang Ming</u>__, Yuchong Hu, Patrick P. C. Lee, Xinjue Zheng, Wenxiang Zhou, and Dan Feng. "AsymCheck: Asymmetric Partitioned Checkpointing for Efficient Large Language Model Training." 2026. In Proceedings of Design Automation Conference 2026 (__Submitted__, __DAC'26__, CCF-A, CSRanking) 


-	__<u>Zhangqiang Ming</u>__, Yuchong Hu, Patrick P. C. Lee, Yuanhao Shu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "Enabling Efficient All-Dimension Top-k Sparsification for High-Performance Distributed DNN Training Systems." Transactions on Architecture and Code Optimization (__Submitted__, TACO, CCF-A)


-	__<u>Zhangqiang Ming</u>__, Yuchong Hu, Patrick P. C. Lee, Yuanhao Shu, Xinjue Zheng, Wenxiang Zhou, and Dan Feng. "Enabling Efficient Tensor Fusion with Sparsification Ahead for High-Performance Distributed DNN Training Systems." Transactions on Parallel and Distributed Systems (__Submitted__, TPDS, CCF-A). 



-	Xinjue Zheng, __<u>Zhangqiang Ming</u>__, Yuchong Hu, Wenxiang Zhou, and Dan Feng. "Saving Memory via Residual Reduction for DNN Training with Compressed Communication." 2025. In Proceedings of the European Conference on Parallel Processing (__EuroPar'25__, CCF-B, CSRanking) [[Code]](https://github.com/zqming-cs) [[Preview]](https://zhangqiangming.github.io/papers/7_Reduce_.pdf)[[Download]](https://zhangqiangming.github.io/papers/7_Reduce_.pdf)



- __<u>Zhangqiang Ming</u>__, Yuchong Hu, Wenxiang Zhou, Xinjue Zheng, and Dan Feng. "Gradient Compression Techniques in Distributed DNNs Training Systems: A Survey and Outlooks." arXiv preprint arXiv:2310.14484 (2023). [[Preview]](https://zhangqiangming.github.io/papers/8_Survey_.pdf)[[Download]](https://zhangqiangming.github.io/papers/8_Survey_.pdf)


- Yong Yang, Chengrui Gao, __<u>Zhangqiang Ming</u>__, Jixiang Guo, Edou Leopold, Junlong Cheng, Jie Zuo, and Min Zhu. "LatLRR-CNN: An infrared and visible image fusion method combining latent low-rank representation and CNN." Multimedia Tools and Applications 82, no. 23 (2023): 36303-36323. (JCR:Q1; IF:3.748) [[Preview]](https://zhangqiangming.github.io/papers/9_LatLRR_.pdf)[[Download]](https://zhangqiangming.github.io/papers/9_LatLRR_.pdf)



- Junlong Cheng, Chengrui Gao, Changlin Li, __<u>Zhangqiang Ming</u>__, Yong Yang, Fengjie Wang, and Min Zhu. "F2RNET: A Full-Resolution Representation Network for Biomedical Image Segmentation." In 2022 IEEE International Conference on Image Processing (ICIP), pp. 2406-2410. IEEE, 2022. [[Preview]](https://zhangqiangming.github.io/papers/10_F2RNET_.pdf)[[Download]](https://zhangqiangming.github.io/papers/10_F2RNET_.pdf)



<!-- __<u>Zhangqiang Ming</u>__ -->
- Cheng, Junlong, Chengrui Gao, Hongchun Lu, __<u>Zhangqiang Ming</u>__, Yong Yang, and Min Zhu. "PL-Net: progressive learning network for medical image segmentation[J]." Frontiers in Bioengineering and Biotechnology, 2024, 12: 1414605. (2024). [[Preview]](https://zhangqiangming.github.io/papers/11_PL-Net_.pdf)[[Download]](https://zhangqiangming.github.io/papers/11_PL-Net_.pdf)



<!-- 🎖 -->
# 🏅 Honors and Awards

### Scholarships
- *2022 – 2023*, First-Class Doctoral Academic Scholarship, Huazhong University of Science and Technology
- *2023 – 2024*, First-Class Doctoral Academic Scholarship, Huazhong University of Science and Technology
- *2024 – 2025*, Third-Class Doctoral Academic Scholarship, Huazhong University of Science and Technology
- *2023 - 2024*, Outstanding Graduate Scholarship, Huazhong University of Science and Technology
- *2023 – 2024*, Doctor of Engineering Training Reform Pilot Scholarship, Huazhong University of Science and Technology
- *2024 – 2025*, Huawei Scholarship, Huazhong University of Science and Technology
- *2020 – 2021*, National Scholarship for Graduate Students (Master's Level)
- *2019 – 2022*, First-Class Graduate Academic Scholarship, Sichuan University
- *2016 – 2017*, First-Class Undergraduate Scholarship
- *2015 – 2016*, National Scholarship for Undergraduate Students


### Awards
- *2025.07*, HPDC2024 International Conference Travel Award (850 USD)
- *2024.06*, HPDC2025 International Conference Travel Award (1600 USD)
- *2023 - 2024*, First Prize, 2nd National College Student Information Storage Technology Competition
- *2023 - 2024*, Best Paper Award, 3rd Annual Academic Conference, School of Computer Science, HUST 
- *2022 - 2023*, Outstanding Graduate Student Leader, Huazhong University of Science and Technology, 
- *2021 - 2022*, Outstanding Graduate of Sichuan Province 
- *2021 - 2022*, Outstanding Student Leader, Sichuan University
- *2019 – 2020*, Outstanding Graduate Student Leader, Sichuan University



<!-- 
### Student Leadership and Service
- *2022 – 2026*, Secretary of the Communist Youth League Branch (Doctoral Cohort 2201), School of Computer Science, Huazhong University of Science and Technology
- *2020 – 2021*, Chair, 9th CCF Student Chapter, Sichuan University
 -->



<!--📖 🎓 -->
# 🎓 Educations
- *2022.09 - 2026.06 (now)*,  Huazhong University of Science and Technology, Ph.D in Computer Science and Technology. 
- *2019.09 - 2019.06*,  Sichuan University, Master's degree in Computer Technology. 



<!-- 💬 -->
# 📑 Invited Talks
- *2025*, ACM Symposium on High-Performance Parallel and Distributed Computing (HPDC2025), University of Notre Dame, USA, Oral Presentation.
- *2024*, ACM Symposium on High-Performance Parallel and Distributed Computing (HPDC2024), University of Pisa, Italy, Oral Presentation.
- *2025*, 2nd CCF China Storage Conference (ChinaStorage2025), Wuhan, China, Poster Presentation.
- *2024*, 1st CCF China Storage Conference (ChinaStorage2024), Guangzhou, China, Poster Presentation.
- *2024*, 3rd Annual Academic Conference, School of Computer Science, Huazhong University of Science and Technology, Wuhan, China, Oral Presentation.
- *2021*, 11th International Conference on Information Science and Technology (ICIST2021), Chengdu, China, In-person Presentation.
- *2021*, 4th Chinese Conference on Pattern Recognition and Computer Vision (PRCV2021), Beijing, China, In-person Presentation.



# 💻 Internships
### Projects
- *2023.06 – 2027.06*, HUST–H3C Joint Laboratory, Storage Construction Project, Intelligent Computing Center, Key Participants.
- *2023.08 – 2026.08*, Shenzhen Natural Science Foundation (General Program), Research on Key Storage Technologies for Distributed DNN Training Systems, Key Participants.
- *2021.09 – 2024.09*, National Key R&D Program – Young Scientist Project, Research on Reliability Coding Theory and Techniques for Large-Scale Parallel Computing Systems, Key Participants.
- *2020.09 – 2023.09*, Shenzhen Natural Science Foundation (General Program), Research on Large-Scale All-Flash Cluster Erasure Coding with Low Redundancy Cost, Key Participants. 
- *2019.09 – 2022.04*, National Key R&D Program, Research and Application of Key Technologies for Target Tracking and Re-Localization, Key Participants.


### Experiences
- *2025.05 – 2026.02*, Intelligent Algorithm Research Institute, China Electronics Hikvision Group, Hangzhou, Zhejiang
- *2021.06 – 2021.09*, Intelligent Algorithm Application Department, Hikvision Research Institute, Chengdu, Sichuan
- *2017.06 – 2018.01*, Product Development Department, Wuhan Tianyu Software Co., Ltd., Wuhan, Hubei
