---
permalink: /life/
title: ""
excerpt: ""
author_profile: true
---

<h1 id="-life">🌿 <span class="lang-en">Life</span><span class="lang-zh" style="display:none">生活</span></h1>

<h2><span class="lang-en">👨‍🍳 My Personal Chef</span><span class="lang-zh" style="display:none">👨‍🍳 我家厨神（御用厨师）</span></h2>

<!-- TODO: Replace placeholder below with actual photo path, e.g. /images/husband.jpg -->
<div style="text-align:center; margin: 1em 0;">
  <img src="/images/life-husband.jpg" alt="My husband" style="max-width:400px; width:100%; border-radius:8px;"
    onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
  <div style="display:none; padding:60px 0; background:#f5f5f5; border-radius:8px; color:#999;">
    📷 <span class="lang-en">Photo coming soon</span><span class="lang-zh">照片待上传</span>
  </div>
</div>

<h2><span class="lang-en">🐱 Taizi, My Cat</span><span class="lang-zh" style="display:none">🐱 猫咪"太子"</span></h2>

<!-- TODO: Replace placeholder below with actual photo path, e.g. /images/taizi.jpg -->
<div style="text-align:center; margin: 1em 0;">
  <img src="/images/life-taizi.jpg" alt="Taizi the cat" style="max-width:400px; width:100%; border-radius:8px;"
    onerror="this.style.display='none'; this.nextElementSibling.style.display='block';">
  <div style="display:none; padding:60px 0; background:#f5f5f5; border-radius:8px; color:#999;">
    📷 <span class="lang-en">Photo coming soon</span><span class="lang-zh">照片待上传</span>
  </div>
</div>

<h2><span class="lang-en">🏃 Hobbies</span><span class="lang-zh" style="display:none">🏃 兴趣爱好</span></h2>

- <span class="lang-en">Half-marathon (*21.0975km, 7/50*)</span><span class="lang-zh" style="display:none">半程马拉松（*21.0975公里，7/50*）</span>
- <span class="lang-en">Travel, photography</span><span class="lang-zh" style="display:none">旅行、摄影</span>
- <span class="lang-en">Running, fitness, badminton</span><span class="lang-zh" style="display:none">跑步、健身、羽毛球</span>

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
