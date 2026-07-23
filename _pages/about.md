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

His research focuses on Software Quality Analysis and Assurance, in particular combining program analysis with neuro-symbolic reasoning and AI agents to advance vulnerability detection and exploitation. 

💬 <span class="email-link" data-u1="kaixuan" data-u2="li" data-h="ntu" data-t1="edu" data-t2="sg" role="button" tabindex="0" aria-label="Send email"></span>


# 🔥 News

* <span style="color:#FC4E2A">**2026.07:**</span> I was invited to serve on the Program Committee of USENIX Security 2027. Welcome to submit your papers.
* <span style="color:#FC4E2A">**2026.06:**</span> I received the Gemini Academic Program Award from Google Cloud.
* <span style="color:#FC4E2A">**2026.05:**</span> I was invited to serve on the Program Committee of FSE 2027 (Research Track). Welcome to submit your papers.
* <span style="color:#FC4E2A">**2026.04:**</span> Our work about evidence-based C/C++ binary third-party library detection was accepted at ISSTA 2026.
* <span style="color:#FC4E2A">**2026.02:**</span> I was invited to serve on the Program Committee of ICSE 2027 (Research Track). Welcome to submit your papers.
* <span style="color:#FC4E2A">**2026.01:**</span> I was awarded the "Young Outstanding Paper Award" by the Shanghai Association of Artificial Intelligence (SAAI).

<details class="news-more" markdown="1">
<summary>Show earlier news</summary>

* <span style="color:#FC4E2A">**2025.12:**</span> Two papers for Neuro-Symbolic vulnerability detection were accepted to FSE 2026 and TSE, respectively.
* <span style="color:#FC4E2A">**2025.11:**</span> My Ph.D. thesis was awarded "The distinguished Ph.D. thesis" at ECNU.

</details>

# 🔍 Curated Literature Resources

Recently, I have been maintaining three curated, community-maintained literature repositories:

- [Hypervisor Testing: Techniques, Challenges, and Future Directions](https://marklee131.github.io/Hypervisor-Testing-Survey/) [![](https://img.shields.io/github/stars/MarkLee131/Hypervisor-Testing-Survey?style=flat-square&logo=github&label=%E2%98%85)](https://github.com/MarkLee131/Hypervisor-Testing-Survey)
- [Static Analyzer Research Papers](https://marklee131.github.io/Static-Analyzer-Research/) [![](https://img.shields.io/github/stars/MarkLee131/Static-Analyzer-Research?style=flat-square&logo=github&label=%E2%98%85)](https://github.com/MarkLee131/Static-Analyzer-Research)
- [Proof-of-Concept (PoC) Research Papers](https://marklee131.github.io/PoC-Research-Papers/) [![](https://img.shields.io/github/stars/MarkLee131/PoC-Research-Papers?style=flat-square&logo=github&label=%E2%98%85)](https://github.com/MarkLee131/PoC-Research-Papers)

The goal is to provide a structured, continuously updated overview of the fields and to reduce repeated literature collection efforts. Contributions, corrections, and suggestions are very welcome.


# 📝 Selected Publications
Notation: * corresponding author, ^ co-first author (as marked in author list). [[Full list]](https://scholar.google.com/citations?user=zmkdR04AAAAJ&hl=en)

- **A Systematic Study on Generating Web Vulnerability Proof-of-Concepts Using Large Language Models**
  - Mengyao Zhao, **Kaixuan Li**^, Lyuye Zhang, Wenjing Dang, Chenggong Ding, Sen Chen, and Zheli Liu
  - [*Preprint: https://arxiv.org/abs/2510.10148*](https://arxiv.org/abs/2510.10148), 2025

- **Real-World Usability of Vulnerability Proof-of-Concepts: A Comprehensive Study**
  - Wenjing Dang, **Kaixuan Li**^, Sen Chen, Zhenwei Zhuo, Lyuye Zhang, and Zheli Liu
  - [*Preprint: https://arxiv.org/pdf/2510.18448*](https://arxiv.org/pdf/2510.18448), 2025

----

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) ![](https://img.shields.io/badge/ISSTA-2026-blue?style=flat-square) **Beyond Similarity Scores: Evidence-Based Third-Party Library Detection for C/C++ Binaries**
  - Chengyue Liu, Zhengzi Xu, Lyuye Zhang, Jiahui Wu, **Kaixuan Li**, and Yang Liu
  - *ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA)*, 2026 (to appear)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/TOSEM-2026-blue?style=flat-square)](https://dl.acm.org/doi/10.1145/3811034) **ARASH: Token-Efficient LLM-Assisted Crash Root Cause Analysis in Fuzz Driver Generation**
  - Maoyi Xie, **Kaixuan Li**\*, Jingquan Ge, Wei Ma, Yuqiang Sun, Ziqiao Kong, Cen Zhang, Dongge Liu, Oliver Chang, and Yang Liu
  - *ACM Transactions on Software Engineering and Methodology (TOSEM)*, 2026
  - [https://dl.acm.org/doi/10.1145/3811034](https://dl.acm.org/doi/10.1145/3811034)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/OOPSLA-2026-blue?style=flat-square)](https://dl.acm.org/doi/10.1145/3798272) **Reframing Paths as Logic: Semantic Segmentation for Vulnerability Detection**
  - Zong Cao, Yuqiang Sun, Zhengzi Xu, **Kaixuan Li**, Yeqi Fu, Yiran Zhang, Ziqiao Kong, and Yang Liu
  - *International Conference on Object-Oriented Programming Systems, Languages, and Applications (OOPSLA 2026)*, 2026
  - [https://dl.acm.org/doi/10.1145/3798272](https://dl.acm.org/doi/10.1145/3798272)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) ![](https://img.shields.io/badge/FSE-2026-blue?style=flat-square) **Understanding the Limitations of C/C++ Binary Third-Party Library Detection Tool: An Empirical Study at Scale**
  - Chengyue Liu, Zhengzi Xu, **Kaixuan Li**, Jiahui Wu, Sihao Qiu, Siyuan Li, Siyang Xiong, Yang Xiao, and Yang Liu
  - *ACM International Conference on the Foundations of Software Engineering (FSE)*, 2026 (to appear)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2026-blue?style=flat-square)](https://doi.org/10.1145/3797065) **GadgetHunter: Region-Based Neuro-Symbolic Detection of Java Deserialization Vulnerabilities**
  - **Kaixuan Li**, Jian Zhang, Chong Wang, Sen Chen, Zong Cao, Min Zhang, and Yang Liu
  - *ACM International Conference on the Foundations of Software Engineering (FSE)*, 2026
  - [https://doi.org/10.1145/3797065](https://doi.org/10.1145/3797065)
  - [*Preprint*](./papers/kaixuan-FSE26_GadgetHunter.pdf)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/TSE-2026-blue?style=flat-square)](https://doi.org/10.1109/TSE.2026.3678424) **DeepFWI: Identifying Bug-Sensitive Warnings with Multi-Modal Code-Warning Semantics**
  - Han Liu, Jian Zhang, Cen Zhang, Xiaohan Zhang, **Kaixuan Li**, Sen Chen, Shang-Wei Lin, Yixiang Chen, Xinghua Li, and Yang Liu
  - *IEEE Transactions on Software Engineering (TSE)*, 2026 (Early Access, pp. 1-17)
  - [https://doi.org/10.1109/TSE.2026.3678424](https://doi.org/10.1109/TSE.2026.3678424)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ICSE-2026-blue?style=flat-square)](https://arxiv.org/abs/2511.06762) **Minimizing Breaking Changes and Redundancy in Mitigating Technical Lag for Java Projects**
  - Rui Lu, Lyuye Zhang, **Kaixuan Li**\*, Min Zhang, and Yixiang Chen
  - *ACM/IEEE International Conference on Software Engineering (ICSE)*, 2026
  - [*Preprint: https://arxiv.org/abs/2511.06762*](https://arxiv.org/abs/2511.06762)

- [![](https://img.shields.io/badge/BlackHat_USA-2025-blue?style=flat-square)](https://blackhat.com/us-25/briefings/schedule/#let-llm-learn-when-your-static-analyzer-actually-gets-it-46444) **Let LLM Learn: When Your Static Analyzer Actually 'Gets It'**
  - Zong Cao, Zhengzi Xu, Yeqi Fu, Yuqiang Sun, **Kaixuan Li**, and Yang Liu
  - *Black Hat USA 2025*, 2025
  - [Official Briefings](https://blackhat.com/us-25/briefings/schedule/#let-llm-learn-when-your-static-analyzer-actually-gets-it-46444)
  - [Video](https://www.youtube.com/watch?v=FPzOgf2EGQE)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2025-blue?style=flat-square)](https://doi.org/10.1109/ASE63991.2025.00013) **Learning from the Past: Real-World Exploit Migration for Smart Contract PoC Generation**
  - Kairan Sun, Zhengzi Xu, **Kaixuan Li**, Lyuye Zhang, Yebo Feng, Daoyuan Wu, and Yang Liu
  - *ACM/IEEE International Conference on Automated Software Engineering (ASE)*, 2025
  - [https://doi.org/10.1109/ASE63991.2025.00013](https://doi.org/10.1109/ASE63991.2025.00013)
  - [*Preprint*](./papers/ASE25_PoCShift.pdf)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ASE-2025-blue?style=flat-square)](https://doi.org/10.1109/ASE63991.2025.00017) **FaultSeeker: LLM-Empowered Framework for Blockchain Transaction Fault Localization**
  - Kairan Sun, Zhengzi Xu, **Kaixuan Li**, Lyuye Zhang, Yuqiang Sun, Liwei Tan, and Yang Liu
  - *ACM/IEEE International Conference on Automated Software Engineering (ASE)*, 2025
  - [https://doi.org/10.1109/ASE63991.2025.00017](https://doi.org/10.1109/ASE63991.2025.00017)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/TSE-2025-blue?style=flat-square)](https://doi.org/10.1109/TSE.2025.3590108) [![](https://img.shields.io/badge/ICSE-2026_J1-1f6feb?style=flat-square)](https://conf.researchr.org/track/icse-2026/icse-2026-journal-first-papers) **ACFix: Guiding LLMs With Mined Common RBAC Practices for Context-Aware Repair of Access Control Vulnerabilities in Smart Contracts**
  - Lyuye Zhang^, **Kaixuan Li**^, Kairan Sun, Daoyuan Wu, Ye Liu, Haoye Tian, and Yang Liu
  - *IEEE Transactions on Software Engineering (TSE)*, vol. 51, no. 9, pp. 2512-2532, 2025. Invited to the ICSE 2026 Journal-First track.
  - [https://doi.org/10.1109/TSE.2025.3590108](https://doi.org/10.1109/TSE.2025.3590108)
  - [*Preprint: https://arxiv.org/pdf/2403.06838.pdf*](https://arxiv.org/pdf/2403.06838.pdf)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/TSE-2024-blue?style=flat-square)](http://arxiv.org/abs/2410.20740) **A Comprehensive Study on Static Application Security Testing (SAST) Tools for Android**
  - Jingyun Zhu^, **Kaixuan Li**^, Sen Chen, Lingling Fan, Junjie Wang, and Xiaofei Xie
  - *IEEE Transactions on Software Engineering (TSE)*, 2024
  - [*Preprint: http://arxiv.org/abs/2410.20740*](http://arxiv.org/abs/2410.20740)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2024-blue?style=flat-square)](https://doi.org/10.1145/3650212.3680305) **PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software**
  - **Kaixuan Li**, Jian Zhang, Sen Chen, Han Liu, Yang Liu, and Yixiang Chen
  - *ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA)*, 2024
  - [https://doi.org/10.1145/3650212.3680305](https://doi.org/10.1145/3650212.3680305)

- [![](https://img.shields.io/badge/CCAAI-2024-blue?style=flat-square)](https://book.yunzhan365.com/poui/tcew/mobile/index.html) **Hybrid Artificial Intelligence: Logic Reasoning for Large Language Models (混成式人工智能：面向大语言模型的逻辑推理)**
  - **Kaixuan Li** and Yixiang Chen
  - *Communications of Chinese Association for Artificial Intelligence (CCAAI)*, 2024, 14(7): 03-07 (In Chinese)
  - [https://book.yunzhan365.com/poui/tcew/mobile/index.html](https://book.yunzhan365.com/poui/tcew/mobile/index.html)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/UsenixSecurity-2024-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han) **Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts**
  - Han Liu, Daoyuan Wu, Yuqiang Sun, Haijun Wang, **Kaixuan Li**, Yang Liu, and Yixiang Chen
  - *USENIX Security Symposium*, 2024
  - [https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han](https://www.usenix.org/conference/usenixsecurity24/presentation/liu-han)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2024-blue?style=flat-square)](https://doi.org/10.1145/3660772) **Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?**
  - **Kaixuan Li**, Yue Xue, Sen Chen, Han Liu, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, and Yixiang Chen
  - *ACM International Conference on the Foundations of Software Engineering (FSE)*, 2024 [<font color="red">ACM SIGSOFT Distinguished Paper Award</font>](https://2024.esec-fse.org/info/awards)
  - [https://doi.org/10.1145/3660772](https://doi.org/10.1145/3660772)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2023-blue?style=flat-square)](https://doi.org/10.1145/3611643.3616270) **Demystifying the Composition and Code Reuse in Solidity Smart Contracts**
  - Kairan Sun, Zhengzi Xu, Chengwei Liu, **Kaixuan Li**, and Yang Liu
  - *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE)*, 2023
  - [https://doi.org/10.1145/3611643.3616270](https://doi.org/10.1145/3611643.3616270)

- ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2023-blue?style=flat-square)](https://doi.org/10.1145/3611643.3616262) **Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java**
  - **Kaixuan Li**^, Sen Chen^, Lingling Fan, Ruitao Feng, Han Liu, Chengwei Liu, Yang Liu, and Yixiang Chen
  - *ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE)*, 2023
  - [https://doi.org/10.1145/3611643.3616262](https://doi.org/10.1145/3611643.3616262)

- [![](https://img.shields.io/badge/JoS-2023-blue?style=flat-square)](http://www.jos.org.cn/1000-9825/6592.htm) **Survey on Trustworthiness Measurement for Artificial Intelligence Systems**
  - Han Liu, **Kaixuan Li**, and Yixiang Chen
  - *Journal of Software (软件学报)*, 2023, 34(8): 3774-3792 (In Chinese)
  - [http://www.jos.org.cn/1000-9825/6592.htm](http://www.jos.org.cn/1000-9825/6592.htm)


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

## Program Committee Member

- **2027**: [USENIX Security](https://www.usenix.org/conference/usenixsecurity27) · [ICSE](https://conf.researchr.org/committee/icse-2027/icse-2027-research-track-program-committee) Research Track · [FSE](https://conf.researchr.org/committee/fse-2027/fse-2027-papers-program-committee) Research Track
- **2026**: [ICSE](https://conf.researchr.org/committee/icse-2026/icse-2026-research-track-research-track) Research Track · [ICSE SEIP](https://conf.researchr.org/committee/icse-2026/icse-2026-software-engineering-in-practice-software-engineering-in-practice) · [FSE](https://conf.researchr.org/committee/fse-2026/fse-2026-research-papers-program-committee) Research Track · [PLDI](https://pldi26.sigplan.org/committee/pldi-2026-src-program-committee) Student Research Competition
- **2025**: [ICSE](https://conf.researchr.org/committee/icse-2025/icse-2025-shadow-research-track-program-committee-shadow-pc) Shadow PC, Research Track · [PLDI](https://pldi25.sigplan.org/committee/pldi-2025-pldi-research-artifacts-artifact-evaluation-committee) Artifact Evaluation · [AILA](http://ailasym.com/AILA2025/AILA2025.html) Symposium
- **2024**: [MSR](https://2024.msrconf.org/committee/msr-2024-junior-pc-technical-papers---junior-program-committee) Junior PC, Technical Papers

## Journal Reviewer

- [TSE](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=32) (IEEE Transactions on Software Engineering)
- [TOSEM](https://dl.acm.org/journal/tosem) (ACM Transactions on Software Engineering and Methodology)
- [TDSC](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8858) (IEEE Transactions on Dependable and Secure Computing)
- [Cybersecurity](https://cybersecurity.springeropen.com/) (Springer Cybersecurity)


# 🎤 Invited Talks

- *2026.07*: "Organizing Vulnerability Knowledge for OpenHarmony." Huawei, Shenzhen, China.
- *2026.05*: "Neuro-Symbolic Vulnerability Detection and Exploitation." East China Normal University, Shanghai, China.
- *2025.04*: "PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software." CCF Technical Committee on Formal Methods, Youth Forum.
- *2024.12*: "Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?" Xi'an Jiaotong University, Xi'an, China.

# ✨ Honors and Awards

* Gemini Academic Program Award from Google Cloud, 2026. (Project: *Reflective Cyber Reasoning*)
* Shanghai Association of Artificial Intelligence (SAAI) Young Outstanding Paper Award（上海市人工智能学会青年科技论文奖）, 2026.
* [The distinguished Ph.D. thesis at East China Normal University](https://yjsy.ecnu.edu.cn/0f/86/c42079a724870/page.htm), 2025.
* The distinguished Ph.D. thesis at the College of Information Technology, East China Normal University, 2025.
* Outstanding Graduate of Shanghai, 2025.
* "Outstanding Student Youth" Award （学生杰出青年）@SEI, East China Normal University, 2025.
* [The President Scholarship of East China Normal University (Graduate)](https://zizhu.ecnu.edu.cn/13/eb/c41428a660459/page.htm), 2024.
* Merit Student of East China Normal University, 2023-2024.
* [National Scholarship, Ministry of Education, China, 2024.](/images/National_Scholarship_Kaixuan_Li.jpg)
* [ACM SIGSOFT Distinguished Paper award, FSE 2024](https://2024.esec-fse.org/info/awards), 2024.
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

    .email-link {
        cursor: pointer;
        color: inherit;
        text-decoration: underline;
        text-decoration-style: dotted;
    }
    .email-link::before {
        content: attr(data-u1) "." attr(data-u2) "\0040" attr(data-h) "." attr(data-t1) "." attr(data-t2);
    }
    .email-link:hover,
    .email-link:focus {
        color: #2a7ae2;
        text-decoration-style: solid;
        outline: none;
    }
</style>

<script>
(function () {
    document.querySelectorAll('.email-link').forEach(function (el) {
        function open() {
            var u = el.getAttribute('data-u1') + '.' + el.getAttribute('data-u2');
            var d = el.getAttribute('data-h') + '.' + el.getAttribute('data-t1') + '.' + el.getAttribute('data-t2');
            var addr = u + String.fromCharCode(64) + d;
            try { if (navigator.clipboard) navigator.clipboard.writeText(addr); } catch (_) {}
            window.location.href = 'mailto:' + addr;
        }
        el.addEventListener('click', open);
        el.addEventListener('keydown', function (e) {
            if (e.key === 'Enter' || e.key === ' ') { e.preventDefault(); open(); }
        });
    });
})();
</script>

<div id="clustrmaps-container">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=xK73SrbAAKlYLUs8vmvb2TVShV7x81eqT_FAU02nk90&cl=ffffff&w=a"></script>
</div>
