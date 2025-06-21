---
title: 프로젝트 포트폴리오
date: 2024-03-25
type: collection

# View.
view: masonry

# Optional header image (relative to `assets/media/` folder).
header:
  caption: ""
  image: ""
---

<style>
/* 강력한 CSS 덮어쓰기 */
html, body {
  background: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%) !important;
}

/* 모든 가능한 배경 클래스 덮어쓰기 */
.page-wrapper, 
.article-container, 
main, 
.main-content,
.wg-collection,
.page-collection,
.hero-widget,
#main,
.site-content {
  background: transparent !important;
  background-color: transparent !important;
  background-image: none !important;
}

/* 페이지 헤더 */
.page-header {
  background: transparent !important;
  padding: 3rem 0 !important;
}

/* 프로젝트 카드 */
.card, .portfolio-item {
  background: rgba(255, 255, 255, 0.95) !important;
  border: 1px solid rgba(99, 102, 241, 0.1) !important;
  border-radius: 12px !important;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08) !important;
  transition: all 0.3s ease !important;
}

.card:hover, .portfolio-item:hover {
  transform: translateY(-3px) !important;
  box-shadow: 0 8px 30px rgba(99, 102, 241, 0.12) !important;
}

/* 다크모드 */
@media (prefers-color-scheme: dark) {
  html, body {
    background: linear-gradient(135deg, #1e293b 0%, #334155 100%) !important;
  }
  
  .card, .portfolio-item {
    background: rgba(30, 41, 59, 0.95) !important;
    border: 1px solid rgba(99, 102, 241, 0.2) !important;
  }
}
</style>

<script>
// JavaScript로 배경색 강제 변경
document.addEventListener('DOMContentLoaded', function() {
  // 모든 가능한 배경 요소들
  const elementsToChange = [
    'html',
    'body', 
    '.page-wrapper',
    '.article-container',
    'main',
    '.main-content',
    '.wg-collection',
    '.page-collection',
    '.hero-widget',
    '#main',
    '.site-content'
  ];
  
  elementsToChange.forEach(selector => {
    const elements = document.querySelectorAll(selector);
    elements.forEach(el => {
      el.style.setProperty('background', 'linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%)', 'important');
      el.style.setProperty('background-color', 'transparent', 'important');
      el.style.setProperty('background-image', 'linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%)', 'important');
    });
  });
  
  // 다크모드 감지
  if (window.matchMedia && window.matchMedia('(prefers-color-scheme: dark)').matches) {
    elementsToChange.forEach(selector => {
      const elements = document.querySelectorAll(selector);
      elements.forEach(el => {
        el.style.setProperty('background', 'linear-gradient(135deg, #1e293b 0%, #334155 100%)', 'important');
        el.style.setProperty('background-image', 'linear-gradient(135deg, #1e293b 0%, #334155 100%)', 'important');
      });
    });
  }
});

// 테마 변경 감지
if (window.matchMedia) {
  window.matchMedia('(prefers-color-scheme: dark)').addEventListener('change', function(e) {
    const elementsToChange = ['html', 'body', '.page-wrapper', 'main'];
    
    elementsToChange.forEach(selector => {
      const elements = document.querySelectorAll(selector);
      elements.forEach(el => {
        if (e.matches) {
          // 다크모드
          el.style.setProperty('background', 'linear-gradient(135deg, #1e293b 0%, #334155 100%)', 'important');
        } else {
          // 라이트모드
          el.style.setProperty('background', 'linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%)', 'important');
        }
      });
    });
  });
}
</script>

<div style="padding: 2rem 0; text-align: center;">
<h1 style="color: #1f2937; font-size: 2.5rem; font-weight: 700; margin-bottom: 1rem;">프로젝트 포트폴리오</h1>
<p style="color: #6b7280; font-size: 1.2rem; line-height: 1.6; max-width: 800px; margin: 0 auto;">AI와 데이터 기술을 활용한 실생활 문제 해결 프로젝트들입니다.</p>
<p style="color: #6b7280; font-size: 1.1rem; line-height: 1.6; max-width: 800px; margin: 1rem auto 0;">각 프로젝트는 실제 사용자의 문제를 해결하고, 사회적 가치를 창출하는 것을 목표로 합니다.</p>
</div>