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

I am a final-year Ph.D. student at Zhejiang University (ZJU), will soon be joining the Independent Cyber Security Lab (ICSL) at Huawei, having been selected for the "Top Minds" program.

My doctoral research is under the guidance of <a href='https://scholar.google.com/citations?user=FCsdj0YAAAAJ'>Prof. Wenyuan Xu</a> and <a href='https://scholar.google.com/citations?user=ax6CbMgAAAAJ'>Prof. Yanjiao Chen</a> at ZJU. Recently, I successfully defended my Ph.D. thesis. My research interests revolve around AI (for) security and privacy, with a particular focus on the security and safety of (multimodal) large language models (LLMs) recently. I have contributed to several publications in leading security conferences such as IEEE S&P, USENIX Security, and ACM CCS. I am open to academic collaborations and welcome inquiries regarding potential research partnerships.

I received my B.E. degree in the College of Electrical Engineering at Zhejiang University in 2019.


<!-- <a href='https://scholar.google.com/citations?user=AE7d_1QAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->


# 🔥 News
- *2024.05.31*: &nbsp;🎉🎉 Successfully defended my Ph.D. thesis!
- *2024.05.20*: &nbsp;🎉🎉 Attended the 45th IEEE Symposium on Security and Privacy in San Francisco, CA, from May 20th to 23rd.
- *2024.04.06*: &nbsp;🎉🎉 Accepted paper for presentation at the 45th IEEE Symposium on Security and Privacy!


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">S&P 2024</div><img src='images/sophon-img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SOPHON: Non-Fine-Tunable Learning to Restrain Task Transferability For Pre-trained Models](https://arxiv.org/pdf/2404.12699)

**Jiangyi Deng**, Shengyuan Pang, Yanjiao Chen, Liangming Xia, Yijie Bai, Haiqin Weng, Wenyuan Xu

[**Code**](https://github.com/ChiangE/Sophon) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper, we introduce a pioneering learning paradigm, *non-fine-tunable learning*, which prevents the pre-trained model from being fine-tuned to indecent tasks while preserving its performance on the original task.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX 2023</div><img src='images/revelio-img-crop.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Catch You and I Can: Revealing Source Voiceprint Against Voice Conversion](https://www.usenix.org/system/files/usenixsecurity23-deng-jiangyi-voiceprint.pdf)

**Jiangyi Deng**, Yanjiao Chen, Yinan Zhong, Qianhao Miao, Xueluan Gong, Wenyuan Xu

[**Presentation**](https://www.youtube.com/watch?v=sz7kKZRT5sg) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper, we make the first attempt to restore the source voiceprint from audios synthesized by voice conversion methods with high credit. This technique may assist investigations of voice conversion-based phone scam.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">USENIX 2023</div><img src='images/vcloak-img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[V-Cloak: Intelligibility-, Naturalness- & Timbre-Preserving Real-Time Voice Anonymization](https://www.usenix.org/system/files/usenixsecurity23-deng-jiangyi-v-cloak.pdf)

**Jiangyi Deng**, Fei Teng, Yanjiao Chen, Xiaofu Chen, Zhaohui Wang, Wenyuan Xu

[**Demo**](https://v-cloak.github.io/) [**Code**](https://github.com/V-Cloak/V-Cloak) [**Presentation**](https://www.youtube.com/watch?v=bDVgfSyjPDo) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper, we develop a voice anonymization system, named V-Cloak, which attains real-time voice anonymization while preserving the intelligibility, naturalness and timbre of the audio.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CCS 2022</div><img src='images/fencesitter-img.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[FenceSitter: Black-box, Content-Agnostic, and Synchronization-Free Enrollment-Phase Attacks on Speaker Recognition Systems](https://dl.acm.org/doi/10.1145/3548606.3559357)

**Jiangyi Deng**, Yanjiao Chen, Wenyuan Xu

[**Presentation**](https://dl.acm.org/doi/10.1145/3548606.3559357) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper, we explore a new attack surface of SRSs by presenting an enrollment-phase attack paradigm, named FenceSitter, where the adversary poisons the SRS using imperceptible adversarial ambient sound when the legitimate user registers into the SRS.
</div>
</div>


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.