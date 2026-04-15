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

I obtained my Ph.D. in 2025 from the College of Electrical Engineering at Zhejiang University and my B.E. degree in 2020 from the College of Automation at Nanjing University of Posts and Telecommunications, and I currently work as a security researcher.

<!-- will soon be joining the Independent Cyber Security Lab (ICSL) at Huawei, having been selected for the "[Top Minds](https://career.huawei.com/reccampportal/portal5/topminds.html)" program. -->

<!-- I obtained my Ph.D. in 2024 and my B.Eng. in 2019 from the College of Electrical Engineering at Zhejiang University, and I currently work as a security researcher. -->

My doctoral research is under the guidance of <a href='https://scholar.google.com/citations?user=FCsdj0YAAAAJ'>Prof. Wenyuan Xu</a> and <a href='https://scholar.google.com/citations?hl=zh-CN&user=9D4UYBoAAAAJ'>Prof. Xiaoyu Ji</a> at ZJU. Recently, my research interests involve around IoT security, with a particular focus on the sensor and algorithm security, as well as malicious power analysis and hardware-level threats. I have contributed to several publications in leading security conferences and journals such as IEEE SP, NDSS, CVPR, ICASSP, and TDSC. I am open to academic collaborations and welcome discussions regarding potential research partnerships.


<!-- I successfully defended my Ph.D. thesis. My research interests revolve around AI (for) security and privacy, with a particular focus on the security and safety of (multimodal) large language models (LLMs) recently. I have contributed to several publications in leading security conferences such as IEEE S&P, USENIX Security, ACM CCS, and NDSS. I am open to academic collaborations and welcome discussions regarding potential research partnerships. -->

<!-- I received my B.E. degree in the College of Electrical Engineering at Zhejiang University in 2019. -->

The template for this page is credited to [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io).

<!-- <a href='https://scholar.google.com/citations?user=AE7d_1QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->


# 🔥 News
<!-- - *2024.08.31*: &nbsp;🎉🎉 Accepted paper for presentation at the NDSS Symposium 2025!
- *2024.08.24*: &nbsp;🎉🎉 Accepted paper for presentation at the ACM Conference on Computer and Communications Security 2024!
- *2024.05.31*: &nbsp;🎉🎉 Successfully defended my Ph.D. thesis!
- *2024.05.24*: &nbsp;🎉🎉 One paper is accepted by ACM CCS 2024!
- *2024.05.20*: &nbsp;🎉🎉 Attended the 45th IEEE Symposium on Security and Privacy in San Francisco, CA, from May 20th to 23rd.
- *2024.04.04*: &nbsp;🎉🎉 One paper is accepted by ACM CCS 2024!
- *2024.03.09*: &nbsp;🎉🎉 Accepted paper for presentation at the 45th IEEE Symposium on Security and Privacy! -->
- *2026.03.03*: &nbsp;🎉🎉 One paper is accepted by the CVPR 2026!
- *2025.08.15*: &nbsp;🎉🎉 One paper is accepted by the NDSS Syposium 2026!
- *2025.05.27*: &nbsp;🎉🎉 Successfully defended my Ph.D. thesis!
- *2025.04.19*: &nbsp;🎉🎉 Attended the ICCCS 2025 in Sichuan, China, and received the certificate of Best Presentation!
- *2025.03.30*: &nbsp;🎉🎉 Accepted paper for presentation at the ICCCS 2025!
- *2025.02.24*: &nbsp;🎉🎉 Attended the Network and Distributed System Security (NDSS) Syposium 2025 in San Diego, CA, from February 24th to 28th.
- *2024.12.21*: &nbsp;🎉🎉 Accepted paper for presentation at the ICASSP 2025!
- *2024.11.27*: &nbsp;🎉🎉 Accepted paper for presentation at the NDSS Symposium 2025!

# 📝 Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2025</div><img src='images/powerradio-img.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PowerRadio: Manipulate Sensor Measurement via Power GND Radiation](https://www.ndss-symposium.org/ndss-paper/powerradio-manipulate-sensor-measurement-via-power-gnd-radiation/)

**Yan Jiang**, Xiaoyu Ji, Yancheng Jiang, Kai Wang, Chenren Xu, Wenyuan Xu

<!-- [**Code**](https://github.com/lin000001/Legilimens) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- In this paper, we open up a new threat vector to sensor measurements. Specifically, we explore the energy conversion of wired signals, and design a power cable-based sensor manipulation attack, named "PowerRadio". PowerRadio can tamper with sensors' readings across sockets and household wiring system.
</div>
</div>

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">TDSC 2024</div><img src='images/marionetto-img.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Marionette: Manipulate Your Touchscreen via a Charging Cable](https://ieeexplore.ieee.org/abstract/document/10288382)

**Yan Jiang**, Xiaoyu Ji, Kai Wang, Chen Yan, Richard Mitev, Ahmad-Reza Sadeghi, Wenyuan Xu

- In this paper, we study the effective detection and protection methods for common-mode (CM) signal injection attacks. In particular, we propose an active suppression device named "GhostBlocker" based on a three -phase common-mode inductor, which enables designers to effectively detect and filter out common-mode interference signals.
</div>
</div> -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">TDSC 2024</div><img src='images/capspeaker-img.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Capspeaker: Injecting Commands to Voice Assistant via Capacitors](https://ieeexplore.ieee.org/abstract/document/10288392)

**Yan Jiang**, Xiaoyu Ji, Juchuan Zhang, Yancheng Jiang, Shui Jiang, Wenyuan Xu

- In this paper, we provide a more comprehensive exploration of "Capspeaker" potential threats and implications. We design a nonlinear model for optimizing the signal crafting process, which significantly improves the recognition success rate of voice assistants. Secondly, we propose a novel software-level defense mechanism that can distinguish malicious and legitimate voice commands. Finally, we expand the attack scenraios applicable to the Capspeaker.
</div>
</div> -->


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">SP 2022</div><img src='images/wight-img.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[WIGHT: Wired Ghost Touch Attack on Capacitive Touchscreens](https://ieeexplore.ieee.org/document/9833740)

**Yan Jiang**, Xiaoyu Ji, Kai Wang, Chen Yan, Richard Mitev, Ahmad-Reza Sadeghi, Wenyuan Xu

- In this paper, we reveal for the first time that the capacitive touchscreens on mobile devices like smartphone, tablet and GPS can be remotely manipulated via power cables. We presenst a practical attack named "WIGHT", which can inject fake touches, alter users' touch operations and disable the touchscreen. We verified the feasibility of WIGHT on touchscreen panels and commercial devices of brands like Apple, Huawei and Xiaomi.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2026</div><img src='images/sok-img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SoK: Understanding the Fundamentals and Implications of Sensor Out-of-band Vulnerabilities](https://www.ndss-symposium.org/wp-content/uploads/2026-s450-paper.pdf)

Shilin Xiao, Wenjun Zhu, **Yan Jiang**, Kai Wang, Peiwang Wang, Chen Yan, Xiaoyu Ji, Wenyuan Xu

- In this paper, we propose a sensor out-of-band (OOB) vulnerability framework that systematically abstracts sensor attack surfaces from a physical perspective. Using a bottom-up approach, we analyze vulnerabilities at the component, sensor, and system levels, and provide insights for improving sensor and CPS security.
</div>
</div>

- [CamPI: Physical Adversarial Examples through Camera Power Signal Injection](). Yanze Ren, Mingyuan Lv, Qinhong Jiang, **Yan Jiang**, Chen Yan, Xiaoyu Ji, Wenyuan Xu. *CVPR*, 2026.

- [False Reality: Uncovering Sensor-induced Human-VR Interaction Vulnerability](https://arxiv.org/abs/2508.08043). Yancheng Jiang, **Yan Jiang**, Ruochen Zhou, Yi-Chao Chen, Xiaoyu Ji, Wenyuan Xu. *arXiv*, 2025.

- [Ghost-SV: Voltage-based Physically-Triggered Backdoor Attack against Speaker Verification](https://ieeexplore.ieee.org/document/11069733). Yancheng Jiang, **Yan Jiang**, Ruochen Zhou, Xiaoyu Ji, Wenyuan Xu. *ICCCS*, 2025.

- [V-Phanton: Voltage-Based Physically-Triggered Backdoor Attack Against Facial Recognition](https://ieeexplore.ieee.org/abstract/document/10888148). **Yan Jiang**, Ruishan Li, Yushi Cheng, Xiaoyu Ji, Wenyuan Xu. *ICASSP*, 2025.

- [Marionette: Manipulate Your Touchscreen via a Charging Cable](https://ieeexplore.ieee.org/abstract/document/10288382). **Yan Jiang**, Xiaoyu Ji, Kai Wang, Chen Yan, Richard Mitev, Ahmad-Reza Sadeghi, Wenyuan Xu. *TDSC*, 2024.

- [Capspeaker: Injecting Commands to Voice Assistant via Capacitors](https://ieeexplore.ieee.org/abstract/document/10288392). **Yan Jiang**, Xiaoyu Ji, Juchuan Zhang, Yancheng Jiang, Shui Jiang, Wenyuan Xu. *TDSC*, 2024.

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2022</div><img src='images/fencesitter-img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FenceSitter: Black-box, Content-Agnostic, and Synchronization-Free Enrollment-Phase Attacks on Speaker Recognition Systems](https://dl.acm.org/doi/10.1145/3548606.3559357)

**Jiangyi Deng**, Yanjiao Chen, Wenyuan Xu

[**Presentation**](https://dl.acm.org/doi/10.1145/3548606.3559357) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper, we explore a new attack surface of SRSs by presenting an enrollment-phase attack paradigm, named FenceSitter, where the adversary poisons the SRS using imperceptible adversarial ambient sound when the legitimate user registers into the SRS.
</div>
</div> -->

<!-- 
- [SafeGen: Mitigating Unsafe Content Generation in Text-to-Image Models](https://arxiv.org/abs/2404.06666). Xinfeng Li, Yuchen Yang, **Jiangyi Deng** (co-first), Chen Yan, Yanjiao Chen, Xiaoyu Ji, Wenyuan Xu. *ACM CCS*, 2024.

- [Alchemy: Data-Free Adversarial Training](). Yijie Bai, Zhongming Ma, Yanjiao Chen, **Jiangyi Deng**, Shengyuan Pang, Yan Liu, Wenyuan Xu. *ACM CCS*, 2024.

- [Dr. Defender: Proactive Detection of Autopilot Drones based on CSI](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10239182). **Jiangyi Deng**, Xiaoyu Ji, Beibei Wang, Bin Wang, Wenyuan Xu. *IEEE TIFS*, 2023.

- [A Nonlinearity-based Secure Face-to-Face Device Authentication for Mobile Devices](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9200789). Xiaoyu Ji, Xinyan Zhou, Chen Yan, **Jiangyi Deng**, Wenyuan Xu. *IEEE TMC*, 2020.

- [Nauth: Secure face-to-face device authentication via nonlinearity](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8737572). Xinyan Zhou, Xiaoyu Ji, Chen Yan, **Jiangyi Deng**, Wenyuan Xu. *IEEE INFOCOM*, 2019. -->
# 📝 Authorized Patents
<!-- - 发明专利：*ZL202510402101.X*-针对生物信息识别系统物理后门攻击的防御装置和方法. (**蒋燕**;徐文渊;冀晓宇)
- 发明专利：*ZL202310264136.2*-一种基于密码芯片功耗分析的异常检测装置和方法. (徐文渊;冀晓宇;**蒋燕**)
- 发明专利：*ZL202311511389.1*-一种基于三相共模电感的有源共模攻击抑制方法和装置. (**蒋燕**;蒋颜丞;徐文渊;冀晓宇)
- 发明专利：*ZL202310446783.5*-一种基于电磁侧信道的设备数字取证装置和取证方法. (徐文渊;冀晓宇;王滨;**蒋燕**;陈加栋;王星)
- 发明专利：*ZL202210706204.1*-一种触摸屏脆弱性分析和防护方法及系统. (徐文渊;冀晓宇;**蒋燕**;闫琛;王凯)
- 发明专利：*ZL202111394732.X*-一种基于扫频技术的传感器安全检测方法和系统. (徐文渊;冀晓宇;**蒋燕**;闫琛)
- 发明专利：*ZL202011073339.6*-基于机器学习的配电终端 DTU 入侵检测方法和系统. (吕志宁;邓巍;宁柏锋;刘威;罗伟峰;徐文渊;冀晓宇;**蒋燕**;李鹏;习伟) -->
- Invention Patent: *ZL202510402101.X* - Defense Device and Method Against Physical Backdoor Attacks in Biometric Recognition Systems. (**Yan Jiang**; Wenyuan Xu; Xiaoyu Ji)
- Invention Patent: *ZL202310264136.2* - Anomaly Detection Device and Method Based on Power Analysis of Cryptographic Chips. (Wenyuan Xu; Xiaoyu Ji; **Yan Jiang**)
- Invention Patent: *ZL202311511389.1* - Active Common-Mode Attack Suppression Method and Device Based on Three-Phase Common-Mode Inductors. (**Yan Jiang**; Yancheng Jiang; Wenyuan Xu; Xiaoyu Ji)
- Invention Patent: *ZL202310446783.5* - Device and Method for Digital Forensics Based on Electromagnetic Side Channels. (Wenyuan Xu; Xiaoyu Ji; Bin Wang; **Yan Jiang**; Jiadong Chen; Xing Wang)
- Invention Patent: *ZL202210706204.1* - Touchscreen Vulnerability Analysis and Protection Method and System. (Wenyuan Xu; Xiaoyu Ji; **Yan Jiang**; Chen Yan; Kai Wang)
- Invention Patent: *ZL202111394732.X* - Sensor Security Detection Method and System Based on Frequency Sweeping Technology. (Wenyuan Xu; Xiaoyu Ji; **Yan Jiang**; Chen Yan)
- Invention Patent: *ZL202011073339.6* - Machine Learning-Based Intrusion Detection Method and System for Distribution Terminal DTU. (Zhining Lv; Wei Deng; Baifeng Ning; Wei Liu; Weifeng Luo; Wenyuan Xu; Xiaoyu Ji; **Yan Jiang**; Peng Li; Wei Xi)

# 🎖 Honors and Awards
- *2025.06*: Outstanding Graduate, Zhejiang University
- *2025.04*: Certificate of Best Presentation, ICCCS 2025. 
- *2024.12*: Kai Li Scholarship, College of Electrical Engineering, Zhejiang University
- *2024.12*: Honor for Graduates-Advanced Group, Zhejiang University
- *2024.12*: Outstanding Graduate Student Cadre, Zhejiang UniversityB
- *2024.12*: Award of Honor for Graduate, Zhejiang University
- *2023.12*: Honor for Graduates-Excellent in Labor Education, Zhejiang University
- *2022.12*: Award of Honor for Graduate, Zhejiang University
- *2022.12*: Honor for Graduates-Civilized Dormitory, Zhejiang University
- *2021.12*: Duan Wei Scholarship, College of Electrical Engineering, Zhejiang University
- *2021.12*: Graduate of Merit/Triple A graduate, Zhejiang University
- *2021.12*: Award of Honor for Graduate, Zhejiang University

# 📖 Educations
- *2020.09 - 2025.06*, Ph.D.
- *2016.09 - 2020.09*, Undergraduate

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 📖 Services
<!-- - Reviewer of *IEEE Transactions on Information Forensics and Security* -->
<!-- - Reviewer of *ACM Transactions on Privacy and Security* --> 
- External Reviewer of "Big Four", *i.e.*, *IEEE SP*, *USENIX Security*, *ACM CCS*, and *NDSS*
- Reviewer of IEEE International Conference on Acoustics, Speech, and Signal (*ICASSP*).
- Certificate for Red Cross First Aider (2021.4-2024.4).
<!-- - Teaching Assistant of *AI and IOT*, at Zhejiang University, *2021.9 - 2022.1*, *2022.9 - 2023.1* -->
<!-- - Teaching Assistant of *Computer Networking*, at Zhejiang University, *2020.9 - 2021.1*, *2021.2 - 2021.6*  -->
<!-- 
<!-- # 💻 Internships -->
<!-- - *2023.05 - 2024.02*, Department of Fundamental Security, [Ant Group](https://www.antgroup.com/), China. -->

<!-- # 🗺️ Visitor Map

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=5kfn1jf6u04&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script> -->

# 🗺️ Hobbies
- Half-marathon (*21.0975km, 7/50*)
<!-- Mar2025Shangyu(**PB 1:57:10**)—Dec2024Hangzhou—Nov2024Huzhou—Mar2024Nanjing—Nov2023ZJU—Dec2023Qiandaohu—May2023Hangzhou. -->
- Travel, photography
- Running, fitness, badminton 