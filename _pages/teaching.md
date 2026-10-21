---
permalink: /teaching/
title: ""
excerpt: ""
author_profile: true
---

<h1 id="-teaching">🎓 <span class="lang-en">Teaching</span><span class="lang-zh" style="display:none">教学</span></h1>

<!-- TODO: Add teaching experience, courses taught, and student mentorship here -->

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
