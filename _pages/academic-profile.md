---
permalink: /academic-profile/
title: ""
excerpt: ""
author_profile: true
---

<h1 id="-educations">📖 <span class="lang-en">Education</span><span class="lang-zh" style="display:none">教育背景</span></h1>

- *2020.09 - 2025.06*, <span class="lang-en">Ph.D., College of Electrical Engineering, Zhejiang University</span><span class="lang-zh" style="display:none">博士，浙江大学电气工程学院</span>
- *2016.09 - 2020.09*, <span class="lang-en">Undergraduate, College of Automation, Nanjing University of Posts and Telecommunications</span><span class="lang-zh" style="display:none">本科，南京邮电大学自动化学院</span>

<h1 id="-services">📖 <span class="lang-en">Services</span><span class="lang-zh" style="display:none">学术服务</span></h1>

- <span class="lang-en">Reviewer for leading international journals and conferences:</span><span class="lang-zh" style="display:none">国际顶级期刊与会议审稿人：</span>
  - <span class="lang-en">*IEEE/ACM Transactions on Networking (ToN): 2026*</span><span class="lang-zh" style="display:none">*IEEE/ACM 网络学报（ToN）：2026*</span>
  - <span class="lang-en">*IEEE Transactions on Information Forensics and Security (TIFS): 2026*</span><span class="lang-zh" style="display:none">*IEEE 信息取证与安全汇刊（TIFS）：2026*</span>
  - <span class="lang-en">*IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP): 2025*</span><span class="lang-zh" style="display:none">*IEEE 国际声学、语音与信号处理会议（ICASSP）：2025*</span>

- <span class="lang-en">Committee Member, Technical Committee on Electromagnetic and Signal Security, China Cyber Security Society (CCSS): 2026–2031</span><span class="lang-zh" style="display:none">中国网络空间安全学会电磁及信号安全专业委员会委员：2026–2031年</span>
- <span class="lang-en">External Reviewer of "Big Four", *i.e.*, *IEEE SP*, *USENIX Security*, *ACM CCS*, and *NDSS*</span><span class="lang-zh" style="display:none">"四大顶会"（*IEEE SP*、*USENIX Security*、*ACM CCS*、*NDSS*）外部审稿人</span>
- <span class="lang-en">Certificate for Red Cross First Aider (2021.4-2024.4).</span><span class="lang-zh" style="display:none">红十字急救员证书（2021.4-2024.4）</span>

<script>
function toggleLang() {
  var lang = document.documentElement.getAttribute('data-lang') === 'zh' ? 'en' : 'zh';
  setLang(lang);
  try { localStorage.setItem('preferredLang', lang); } catch(e) {}
}

function setLang(lang) {
  document.documentElement.setAttribute('data-lang', lang);
  var enEls = document.querySelectorAll('.lang-en');
  var zhEls = document.querySelectorAll('.lang-zh');
  for (var i = 0; i < enEls.length; i++) {
    enEls[i].style.display = lang === 'en' ? '' : 'none';
  }
  for (var i = 0; i < zhEls.length; i++) {
    zhEls[i].style.display = lang === 'zh' ? '' : 'none';
  }
  var btn = document.getElementById('lang-toggle');
  if (btn) btn.textContent = lang === 'zh' ? 'EN' : '中文';
}

document.addEventListener('DOMContentLoaded', function() {
  var saved = 'en';
  try { saved = localStorage.getItem('preferredLang') || 'en'; } catch(e) {}
  setLang(saved);
});
</script>
