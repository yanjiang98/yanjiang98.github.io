---
permalink: /awards/
title: ""
excerpt: ""
author_profile: true
---

<h1 id="-honors-and-awards">🎖 <span class="lang-en">Honors and Awards</span><span class="lang-zh" style="display:none">荣誉奖励</span></h1>

- *2025.06*: <span class="lang-en">Outstanding Graduate, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学优秀毕业生</span>
- *2025.04*: <span class="lang-en">Certificate of Best Presentation, ICCCS 2025.</span><span class="lang-zh" style="display:none">ICCCS 2025最佳报告证书</span>
- *2024.12*: <span class="lang-en">Kai Li Scholarship, College of Electrical Engineering, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学电气工程学院凯黎奖学金</span>
- *2024.12*: <span class="lang-en">Honor for Graduates-Advanced Group, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学研究生荣誉称号——先进集体</span>
- *2024.12*: <span class="lang-en">Outstanding Graduate Student Cadre, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学优秀研究生干部</span>
- *2024.12*: <span class="lang-en">Award of Honor for Graduate, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学研究生荣誉称号</span>
- *2023.12*: <span class="lang-en">Honor for Graduates-Excellent in Labor Education, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学研究生荣誉——劳动教育优秀</span>
- *2022.12*: <span class="lang-en">Award of Honor for Graduate, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学研究生荣誉称号</span>
- *2022.12*: <span class="lang-en">Honor for Graduates-Civilized Dormitory, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学研究生荣誉——文明寝室</span>
- *2021.12*: <span class="lang-en">Duan Wei Scholarship, College of Electrical Engineering, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学电气工程学院段威奖学金</span>
- *2021.12*: <span class="lang-en">Graduate of Merit/Triple A graduate, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学三好研究生</span>
- *2021.12*: <span class="lang-en">Award of Honor for Graduate, Zhejiang University</span><span class="lang-zh" style="display:none">浙江大学研究生荣誉称号</span>

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
