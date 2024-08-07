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

[Kaixuan Li](https://kaixuanli-ecnu.github.io/) (The "X" in "Kaixuan" is pronounced like the "sh" in "shear) is now a final-year Ph.D. candidate in the Software Engineering Institute at [East China Normal University (ECNU)](https://www.ecnu.edu.cn/), under the supervision of [Prof. Yixiang Chen](https://faculty.ecnu.edu.cn/_s43/cyx/main.psp). Before that, I received my B.S. degree in Software Engineering Institute from ECNU in 2020. 
I am also a visiting Ph.D. student and research assistant at [Nanyang Technological University](https://www.ntu.edu.sg/) under the supervision of [Prof. Yang Liu](https://personal.ntu.edu.sg/yangliu/) during 2022-2025.

My research focuses on Trustworthy Software, particularly in areas such as **Open Source Security** and **Smart Contract Security**. 
My ongoing research explores advanced program analysis and the application of large language models (LLMs) for enhancing software security. 

I am actively seeking opportunities for **collaboration** and am interested in **postdoctoral positions** starting in 2025. If you are looking for a dedicated and passionate researcher to contribute to and advance these critical areas, please feel free to contact me.

# 🔥 News
* July 2024: I am selected as a Shadow Research Track Program Committee Member within ICSE 2025!
* July 2024: Our paper "PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software" was accepted by ISSTA 2024. ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2024-blue?style=flat-square)](https://2024.issta.org/)
* June 2024: Our paper "Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?" has won an [ACM SIGSOFT Distinguished Paper award](https://2024.esec-fse.org/info/awards)! 🏆
* May 2024: Our paper "Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts" was accepted by Usenix Security 2024. ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/Usenix_Security-2024-blue?style=flat-square)](https://www.usenix.org/conference/usenixsecurity24)
* April 2024: Our paper "Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?" was accepted by FSE 2024. ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/FSE-2024-blue?style=flat-square)](https://conf.researchr.org/home/fse-2024)
* July 2023: Our paper "Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java" was accepted by ESEC/FSE 2023. ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ESEC/FSE-2023-blue?style=flat-square)](https://2023.esec-fse.org/details/fse-2023-research-papers/21/Comparison-and-Evaluation-on-Static-Application-Security-Testing-SAST-Tools-for-Java)
* July 2023: Our paper "Demystifying the Composition and Code Reuse in Solidity Smart Contracts" was accepted by ESEC/FSE 2023. ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ESEC/FSE-2023-blue?style=flat-square)](https://2023.esec-fse.org/details/fse-2023-research-papers/29/Demystifying-the-Composition-and-Code-Reuse-in-Solidity-Smart-Contracts)
* January 2023: Our paper "A Comprehensive Study on Quality Assurance Tools for Java" was accepted by ISSTA 2023. ![](https://img.shields.io/badge/CCF-A-red?style=flat-square) [![](https://img.shields.io/badge/ISSTA-2023-blue?style=flat-square)](https://2023.issta.org/details/issta-2023-technical-papers/16/A-Comprehensive-Study-on-Quality-Assurance-Tools-for-Java)



# 📝 Selected Publications 
^ indicates equal contribution.
- *(ISSTA 2024, CCF-A)* **Kaixuan Li**, Jian Zhang, Sen Chen, Han Liu, Yang Liu, and Yixiang Chen. 2024. PatchFinder: A Two-Phase Approach to Security Patch Tracing for Disclosed Vulnerabilities in Open-Source Software. In Proceedings of the 33rd ACM SIGSOFT International Symposium on Software Testing and Analysis (ISSTA ’24), September 16–20, 2024, Vienna, Austria. ACM, New York, NY, USA, 13 pages. https://doi.org/10.1145/3650212.3680305. [https://arxiv.org/pdf/2407.17065](https://arxiv.org/pdf/2407.17065)
- *(Preprint)* Han Liu, Jian Zhang, Cen Zhang, Xiaohan Zhang, **Kaixuan Li**, Sen Chen, Shang-Wei Lin, Yixiang Chen, Xinhua Li, and Yang Liu. 2024. "FineWAVE: Fine-Grained Warning Verification of Bugs for Automated Static Analysis Tools." arXiv preprint arXiv:2403.16032 (2024), [https://arxiv.org/pdf/2403.16032.pdf](https://arxiv.org/pdf/2403.16032.pdf)
- *(Preprint)* Lyueye Zhang^, **Kaixuan Li**^, Kairan Sun, Daoyuan Wu, Ye Liu, Haoye Tian, and Yang Liu. 2024. "Acfix: Guiding LLMs with mined common RBAC practices for context-aware repair of access control vulnerabilities in smart contracts." arXiv preprint arXiv:2403.06838 (2024), [https://arxiv.org/pdf/2403.06838.pdf](https://arxiv.org/pdf/2403.06838.pdf)
- *(Usenix Security 2024, CCF-A)* Han Liu, Daoyuan Wu, Yuqiang Sun, Haijun Wang, **Kaixuan Li**, Yang Liu, and Yixiang Chen. 2024. "Using My Functions Should Follow My Checks: Understanding and Detecting Insecure OpenZeppelin Code in Smart Contracts". In Proceedings of the 2024 USENIX Security Symposium (USENIX Security'24).
- *(FSE 2024, CCF-A)* **Kaixuan Li**, Yue Xue, Sen Chen, Han Liu, Kairan Sun, Ming Hu, Haijun Wang, Yang Liu, and Yixiang Chen. 2024. Static Application Security Testing (SAST) Tools for Smart Contracts: How Far Are We?. Proc. ACM Softw. Eng. 1, FSE, Article 65 (July 2024), 24 pages. [https://doi.org/10.1145/3660772](https://doi.org/10.1145/3660772). [Preprint](https://arxiv.org/pdf/2404.18186). [<font color ="red"> ACM SIGSOFT Distinguished Paper award </font>](https://2024.esec-fse.org/info/awards) 🏆
- *(ESEC/FSE 2023, CCF-A)* **Kaixuan Li**^, Sen Chen^, Lingling Fan, Ruitao Feng, Han Liu, Chengwei Liu, Yang Liu, and Yixiang Chen. 2023. "Comparison and Evaluation on Static Application Security Testing (SAST) Tools for Java". United States, In Proceedings of the 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2023); 3 December-9 December 2023, Pages:921–933, [https://doi.org/10.1145/3611643.3616262](https://doi.org/10.1145/3611643.3616262). 
- *(ESEC/FSE 2023, CCF-A)* Kairan Sun, Zhengzi Xu, Chengwei Liu, **Kaixuan Li**, and Yang Liu. 2023. "Demystifying the Composition and Code Reuse in Solidity Smart Contracts." United States, In Proceedings of the 31st ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE 2023); December 3-9 2023, Pages:796-807, [https://dl.acm.org/doi/pdf/10.1145/3611643.3616270](https://dl.acm.org/doi/pdf/10.1145/3611643.3616270).
- *(ISSTA 2023, CCF-A)* Han Liu, Sen Chen, Ruitao Feng, Chengwei Liu, **Kaixuan Li**, Zhengzi Xu, Liming Nie, Yang Liu, and Yixiang Chen. 2023. "A Comprehensive Study on Quality Assurance Tools for Java", United States, In Proceedings of the 32nd International Symposium on Software Testing and Analysis (ISSTA); 17 July-21 July 2023, Pages:285–297, [https://doi.org/10.1145/3597926.3598056](https://doi.org/10.1145/3597926.3598056).
- *(JoS, CCF-A in Chinese)* Han Liu, **Kaixuan Li**, and Yixiang Chen. "Survey on Trustworthiness Measurement for Artificial Intelligence Systems". Ruan Jian Xue Bao/Journal of Software, 2023, 34(8): 3774–3792 (in Chinese), [http://www.jos.org.cn/1000-9825/6592.htm](http://www.jos.org.cn/1000-9825/6592.htm).

# 📖 Educations
- *2020.09 - 2025.06 (expected)*, Ph.D. student/candidate, Software Engineering Institute, East China Normal University.
- *2023.09 - 2025.04*, Research assistant, [Continental-NTU Corporate Lab](https://www.ntu.edu.sg/continental-ntu), Nanyang Technological University.
- *2022.09 - 2023.09*, Visiting Ph.D. student, School of Computer Science and Engineering, Nanyang Technological University.
- *2016.09 - 2020.06*, Bachelor of Software Engineering, Software Engineering Institute, East China Normal University.


# 📚 Academic Services

## Reviewer:
* [Transactions on Software Engineering and Methodology](https://dl.acm.org/journal/tosem)
* [Cybersecurity](https://cybersecurity.springeropen.com/)

## Shadow/Junior Program Committee Member:
* [ICSE 2025](https://conf.researchr.org/track/icse-2025/icse-2025-shadow-research-track-program-committee)
* [MSR 2024](https://2024.msrconf.org/committee/msr-2024-junior-pc-technical-papers---junior-program-committee)

## Co-reviewer:
* [ASE 2024](https://conf.researchr.org/track/ase-2024/ase-2024-research)
* [S&P 2025](https://www.ieee-security.org/TC/SP2025/cfpapers.html)
* [CCS 2024](https://www.sigsac.org/ccs/CCS2024/call-for/call-for-papers.html)
* [ISSTA 2024](https://2024.issta.org/track/issta-2024-papers)
* [ICSE 2024](https://conf.researchr.org/track/icse-2024/icse-2024-research-track?)
* [WWW 2024](https://www2024.thewebconf.org/)
* [ASE 2023](https://conf.researchr.org/home/ase-2023)
* [ESEC/FSE 2023](https://2023.esec-fse.org/)
* [ASE 2022](https://conf.researchr.org/home/ase-2022)
* [Frontiers of Computer Science](https://www.springer.com/journal/11704)
* [ESTC 2022](https://estc2022.github.io/index.html)
* [AILA 2023](http://ailasym.com/AILA2023/index.html)
* [AILA 2022](http://ailasym.com/AILA2022/index.html)
* [Journal of Software](https://www.jos.org.cn/jos/home)


# 🎖 Honors and Awards
* ACM SIGSOFT Distinguished Paper award, FSE 2024, 2024.
* "Student Technological Excellence" Award (学生科技英才) @SEI, East China Normal University, 2024.
* Merit Student of East China Normal University, 2022-2023.
* Visiting Ph.D. Student Scholarship of China Scholarship Council, 2022-2023.
* Merit Student of East China Normal University, 2021-2022.
* "Boke City" Merit Student Scholarship, 2021-2022.
* Merit Student of East China Normal University, 2020-2021.
* "HUAWEI CUP" The 18th China Post-Graduate Mathematical Contest in Modelling 3rd Prize, 2021.
* "HUAWEI CUP" The 17th China Post-Graduate Mathematical Contest in Modelling 3rd Prize, 2020.
* Outstanding Graduate of Shanghai, 2020.
* Merit Award for "YOOZOO CUP" Shanghai University Programming Invitational Tournament, 2018.
* "ZHIXING CUP" Shanghai Undergraduate Social Practice Project 2nd Prize, 2017.
* Advanced Individual Award for Social Practice of East China Normal University, 2017.
* Best Project Award for Social Practice in East China Normal University, 2017.
* People's Finance Bank Scholarship, 2017.



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
