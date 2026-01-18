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

[Kaixuan Li](https://kaixuanli-ecnu.github.io/) (The "X" in "Kaixuan" is pronounced like the "sh" in "shear") is a postdoctoral research fellow at [Nanyang Technological University](https://www.ntu.edu.sg/), working with [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/). 
He got his Ph.D. degree from the Software Engineering Institute at [East China Normal University (ECNU)](https://www.ecnu.edu.cn/), under the supervision of [Prof. Yixiang Chen](https://faculty.ecnu.edu.cn/_s43/cyx/main.psp). 
Before that, he received a B.S. degree in Software Engineering from ECNU in 2020. 

His research focuses on Software Quality Analysis and Assurance, particularly in exploring program analysis and applying large language models (LLMs) to enhance software security. 

💬 kaixuan.li AT ntu.edu.sg


# 🔥 News

* <span style="color:#FC4E2A">**2026.01:**</span> I was awarded the "Young Outstanding Research Paper Award" by the Shanghai Association of Artificial Intelligence (SAAI). Thank you for this recognition!
* <span style="color:#FC4E2A">**2025.12:**</span> Two papers for Neuro-Symbolic vulnerability detection were accepted to FSE 2026 and TSE, respectively.
* <span style="color:#FC4E2A">**2025.11:**</span> My Ph.D. thesis was awarded "The distinguished Ph.D. thesis" at ECNU!
* <span style="color:#FC4E2A">**2025.10:**</span> Our paper for OSS quality assurance was accepted to ICSE 2026.
* <span style="color:#FC4E2A">**2025.09:**</span> I was selected as a PC member within ICSE 2026 Software Engineering In Practice. Welcome to submit your papers!
* <span style="color:#FC4E2A">**2025.09:**</span> Two papers for smart contract security assurance were accepted to ASE 2025. 
* <span style="color:#FC4E2A">**2025.06:**</span> I was selected as a PC member within FSE 2026. Welcome to submit your papers!
* <span style="color:#FC4E2A">**2025.06:**</span> My Ph.D. thesis was awarded "The distinguished Ph.D. thesis" at the College of Information Technology, ECNU!
* <span style="color:#FC4E2A">**2025.04:**</span> I was honored to be selected as the "Outstanding Graduate of Shanghai". Thank you for this recognition!
* <span style="color:#FC4E2A">**2025.01:**</span> I was selected as a PC member within ICSE 2026. Welcome to submit your papers!


# 🔍 Curated Literature Resources

Recently, I have been maintaining two curated, community-maintained literature repositories:

- [Static Analyzer Research Papers](https://marklee131.github.io/Static-Analyzer-Research/)
- [Proof-of-Concept (PoC) Research Papers](https://marklee131.github.io/PoC-Research-Papers/). 

The goal is to provide a structured, continuously updated overview of the fields and to reduce repeated literature collection efforts. Contributions, corrections, and suggestions are very welcome.

# 📝 Selected Publications 
^: co-first author *: corresponding author.

- <span style="color:#337AB7">[*Preprint*]</span> Mengyao Zhao, **Kaixuan Li^**, Lyuye Zhang, Wenjing Dang, Chenggong Ding, Sen Chen, and Zheli Liu. 2025. "A Systematic Study on Generating Web Vulnerability Proof-of-Concepts Using Large Language Models." [Preprint: https://arxiv.org/abs/2510.10148](https://arxiv.org/abs/2510.10148).

- <span style="color:#337AB7">[*Preprint*]</span> Wenjing Dang, **Kaixuan Li^**, Sen Chen, Zhenwei Zhuo, Lyuye Zhang, and Zheli Liu 2025. "Real-World Usability of Vulnerability Proof-of-Concepts: A Comprehensive Study." [Preprint: https://arxiv.org/pdf/2510.18448](https://arxiv.org/pdf/2510.18448).

----

- <span style="color:#337AB7">[*FSE 2026*]</span> **Kaixuan Li**, Jian Zhang, Chong Wang, Sen Chen, Zong Cao, Min Zhang, and Yang Liu. 2026. "GadgetHunter: Region-Based Neuro-Symbolic Detection of Java Deserialization Vulnerabilities." (to appear)

- <span style="color:#337AB7">[*TSE*]</span> Han Liu, Jian Zhang, Cen Zhang, Xiaohan Zhang, **Kaixuan Li**, Sen Chen, Shang-Wei Lin, Yixiang Chen, Xinghua Li, and Yang Liu, "DeepFWI: Identifying Bug-Sensitive Warnings with Multi-Modal Code-Warning Semantics." (to appear)

- <span style="color:#337AB7">[*ICSE 2026*]</span> Rui Lu, Lyuye Zhang, **Kaixuan Li***, Min Zhang, and Yixiang Chen. 2025. "Minimizing Breaking Changes and Redundancy in Mitigating Technical Lag for Java Projects." [Preprint: https://arxiv.org/abs/2511.06762](https://arxiv.org/abs/2511.06762)
- <span style="color:#337AB7">[*ASE 2025*]</span> Kairan Sun, Zhengzi Xu, **Kaixuan Li**, Lyuye Zhang, Yebo Feng, Daoyuan Wu, and Yang Liu. 2025. "Learning from the Past: Real-World Exploit Migration for Smart Contract PoC Generation." (to appear)
- <span style="color:#337AB7">[*ASE 2025*]</span> Kairan Sun, Zhengzi Xu, **Kaixuan Li**, Lyuye Zhang, Yuqiang Sun, Liwei Tan, and Yang Liu. 2025. "FaultSeeker: LLM-Empowered Framework for Blockchain Transaction Fault Localization." (to appear)

- <span style="color:#337AB7">[*TSE*]</span> Lyueye Zhang^, **Kaixuan Li**^, Kairan Sun, Daoyuan Wu, Ye Liu, Haoye Tian, and Yang Liu. 2024. "Acfix: Guiding LLMs with mined common RBAC practices for context-aware repair of access control vulnerabilities in smart contracts." arXiv preprint arXiv:2403.06838 (2024), [Preprint: https://arxiv.org/pdf/2403.06838.pdf](https://arxiv.org/pdf/2403.06838.pdf)

- <span style="color:#337AB7">[*ISSTA 2025*]</span> Lyuye Zhang, Jiahui Wu, Chengwei Liu, **Kaixuan Li**, Xiaoyu Sun, Lida Zhao, Chong Wang, and Yang Liu. 2025.
 Fixing Outside the Box: Uncovering Tactics for Open-Source Security Issue Management. Proc. ACM Softw. Eng. 2, ISSTA, Article ISSTA 100 (July 2025), 23 pages. https://doi.org/10.1145/3728977.

- <span style="color:#337AB7">[*TSE*]</span> Jingyun Zhu^, **Kaixuan Li**^, Sen Chen, Lingling Fan, Junjie Wang, and Xiaofei Xie. 2024. A Comprehensive Study on Static Application Security Testing (SAST) Tools for Android. IEEE Transactions on Software Engineering. [Preprint: http://arxiv.org/abs/2410.20740](http://arxiv.org/abs/2410.20740).
- <span style="color:#337AB7">[*ISSTA 2024*]</span> **Kaixuan Li**, Jian Zhang, Sen Chen, Han Liu, Yang Liu, and Yixiang Chen. "PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software." In Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis, pp. 590-602. 2024. [https://doi.org/10.1145/3650212.3680305](https://doi.org/10.1145/3650212.3680305).
- <span style="color:#337AB7">[*CCAAI*]</span> **Kaixuan Li** and Yixiang Chen. Hybrid Artificial Intelligence: Logic Reasoning for Large Language Models (混成式人工智能：面向大语言模型的逻辑推理), Communications of Chinese Association for Artificial Intelligence, 2024 14(7): 03-07 (In Chinese). [https://book.yunzhan365.com/poui/tcew/mobile/index.html](https://book.yunzhan365.com/poui/tcew/mobile/index.html).
- <span style="color:#337AB7">[*USENIX Security 2024*]</span> Han Liu, Daoyuan Wu, Yuqiang Sun, Haijun Wang, **Kaixuan Li**, Yang Liu, and Yixiang Chen. 2024. "Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts". In Proceedings of the 2024 USENIX Security Symposium (USENIX Security'24).
- <span style="color:#337AB7">[*FSE 2024*]</span> **Kaixuan Li**, Yue Xue, Sen Chen, Han Liu, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, and Yixiang Chen. 2024. Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?. Proc. ACM Softw. Eng. 1, FSE, Article 65 (July 2024), 24 pages. [https://doi.org/10.1145/3660772](https://doi.org/10.1145/3660772). [<font color ="red"> ACM SIGSOFT Distinguished Paper award </font>](https://2024.esec-fse.org/info/awards) 🏆
- <span style="color:#337AB7">[*FSE 2023*]</span> Kairan Sun, Zhengzi Xu, Chengwei Liu, **Kaixuan Li**, and Yang Liu. 2023. "Demystifying the Composition and Code Reuse in Solidity Smart Contracts." United States, In Proceedings of the 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2023); December 3-9 2023, Pages:796-807, [https://doi.org/10.1145/3611643.3616270](https://doi.org/10.1145/3611643.3616270).
- <span style="color:#337AB7">[*FSE 2023*]</span> **Kaixuan Li**^, Sen Chen^, Lingling Fan, Ruitao Feng, Han Liu, Chengwei Liu, Yang Liu, and Yixiang Chen. 2023. "Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java". United States, In Proceedings of the 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2023); 3 December-9 December 2023, Pages:921–933, [https://doi.org/10.1145/3611643.3616262](https://doi.org/10.1145/3611643.3616262). [PDF](./papers/java-sast-fse23.pdf)
- <span style="color:#337AB7">[*ISSTA 2023*]</span> Han Liu, Sen Chen, Ruitao Feng, Chengwei Liu, **Kaixuan Li**, Zhengzi Xu, Liming Nie, Yang Liu, and Yixiang Chen. 2023. "A Comprehensive Study on Quality Assurance Tools for Java", United States, In Proceedings of the 32nd International Symposium on Software Testing and Analysis (ISSTA); 17 July-21 July 2023, Pages:285–297, [https://doi.org/10.1145/3597926.3598056](https://doi.org/10.1145/3597926.3598056).
- <span style="color:#337AB7">[*JoS, (软件学报)*]</span> Han Liu, **Kaixuan Li**, and Yixiang Chen. "Survey on Trustworthiness Measurement for Artificial Intelligence Systems". Ruan Jian Xue Bao/Journal of Software, 2023, 34(8): 3774–3792 (in Chinese), [http://www.jos.org.cn/1000-9825/6592.htm](http://www.jos.org.cn/1000-9825/6592.htm).

# 📖 Education

- *2020.09 - 2025.06*, Ph.D. in Software Engineering, Software Engineering Institute, East China Normal University.
- *2022.09 - 2023.09*, Visiting Ph.D. student, School of Computer Science and Engineering, Nanyang Technological University.
- *2016.09 - 2020.06*, Bachelor in Software Engineering, Software Engineering Institute, East China Normal University.

# 💻 Teaching

## Teaching Assistant

- Hardware-Software Co-design (软硬件协同设计)
  - Post-graduate course, East China Normal University, 2021.09-2022.01

- Optimization and design of intelligent systems (智能系统优化设计)
  - Undergraduate course, East China Normal University, 2021.02-2021.06

# 📚 Academic Services

- Reviewer/Program Committee Member:
[ICSE 2026](https://conf.researchr.org/committee/icse-2026/icse-2026-research-track-research-track), [ICSE 2026 SEIP](https://conf.researchr.org/committee/icse-2026/icse-2026-software-engineering-in-practice-software-engineering-in-practice), [FSE 2026](https://conf.researchr.org/committee/fse-2026/fse-2026-research-papers-program-committee), [PLDI 2025 Artifact Evaluation](https://pldi25.sigplan.org/committee/pldi-2025-pldi-research-artifacts-artifact-evaluation-committee), [TDSC](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858), [TOSEM](https://dl.acm.org/journal/tosem), [Cybersecurity](https://cybersecurity.springeropen.com/), [AILA 2025](http://ailasym.com/AILA2025/AILA2025.html)

- Shadow/Junior Program Committee Member: [ICSE 2025](https://conf.researchr.org/committee/icse-2025/icse-2025-shadow-research-track-program-committee-shadow-pc), [MSR 2024](https://2024.msrconf.org/committee/msr-2024-junior-pc-technical-papers---junior-program-committee)


# 🎖 Honors and Awards

* Shanghai Association of Artificial Intelligence (SAAI) Young Outstanding Research Paper Award（上海市人工智能学会青年科技论文奖）, 2026.
* [The distinguished Ph.D. thesis at East China Normal University](https://yjsy.ecnu.edu.cn/0f/86/c42079a724870/page.htm), 2025.
* The distinguished Ph.D. thesis at the College of Information Technology, East China Normal University, 2025.
* Outstanding Graduate of Shanghai, 2025.
* "Outstanding Student Youth" Award （学生杰出青年）@SEI, East China Normal University, 2025.
* [The President Scholarship of East China Normal University (Graduate)](https://zizhu.ecnu.edu.cn/13/eb/c41428a660459/page.htm), 2024.
* Merit Student of East China Normal University, 2023-2024.
* [National Scholarship, Ministry of Education, China, 2024.](/images/National_Scholarship_Kaixuan_Li.jpg)
* ACM SIGSOFT Distinguished Paper award, FSE 2024, 2024.
* "Student Technological Excellence" Award (学生科技英才) @SEI, East China Normal University, 2024.
* Visiting Ph.D. Student Scholarship of China Scholarship Council, 2022-2023.
* Merit Student of East China Normal University, 2022-2023.
* Merit Student of East China Normal University, 2021-2022.
* Merit Student of East China Normal University, 2020-2021.
* "HUAWEI CUP" The 18th China Post-Graduate Mathematical Contest in Modelling 3rd Prize, 2021.
* "HUAWEI CUP" The 17th China Post-Graduate Mathematical Contest in Modelling 3rd Prize, 2020.
* Outstanding Graduate of Shanghai, 2020.



<style>
    #clustrmaps-container {
        /* transform: scale(0.5); */
        transform-origin: top left;
        width: 200px; /* Adjust this value based on your desired width */
        height: 150px; /* Adjust this value based on your desired height */
        overflow: hidden; /* This will hide any overflow content */
        
        /* Centering the container horizontally */
        margin-left: auto;
        margin-right: auto;
        display: block;
    }
</style>

<div id="clustrmaps-container">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=xK73SrbAAKlYLUs8vmvb2TVShV7x81eqT_FAU02nk90&cl=ffffff&w=a"></script>
</div>
