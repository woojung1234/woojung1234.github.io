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
/* 프로젝트 페이지 전체 배경 색상 변경 */
body {
  background: linear-gradient(135deg, #f8fafc 0%, #e2e8f0 100%) !important;
}

/* 프로젝트 페이지 컨테이너 스타일링 */
.page-wrapper, .article-container, main {
  background: transparent !important;
}

/* 프로젝트 카드 배경 개선 */
.card, .portfolio-item {
  background: rgba(255, 255, 255, 0.9) !important;
  border: 1px solid rgba(99, 102, 241, 0.1) !important;
  border-radius: 12px !important;
  box-shadow: 0 4px 20px rgba(99, 102, 241, 0.1) !important;
  transition: all 0.3s ease !important;
}

.card:hover, .portfolio-item:hover {
  transform: translateY(-5px) !important;
  box-shadow: 0 8px 30px rgba(99, 102, 241, 0.15) !important;
}

/* 프로젝트 제목 스타일링 */
.page-header h1 {
  color: #1f2937 !important;
  text-shadow: 0 2px 4px rgba(0,0,0,0.1) !important;
}

/* 프로젝트 설명 텍스트 */
.page-header p {
  color: #4b5563 !important;
}

/* 다크모드 대응 */
@media (prefers-color-scheme: dark) {
  body {
    background: linear-gradient(135deg, #1e293b 0%, #334155 100%) !important;
  }
  
  .card, .portfolio-item {
    background: rgba(30, 41, 59, 0.9) !important;
    border: 1px solid rgba(99, 102, 241, 0.2) !important;
  }
  
  .page-header h1 {
    color: white !important;
  }
  
  .page-header p {
    color: #cbd5e1 !important;
  }
}
</style>

<div style="padding: 2rem 0; text-align: center;">
<h1 style="color: #1f2937; font-size: 2.5rem; font-weight: 700; margin-bottom: 1rem;">프로젝트 포트폴리오</h1>
<p style="color: #6b7280; font-size: 1.2rem; line-height: 1.6; max-width: 800px; margin: 0 auto;">AI와 데이터 기술을 활용한 실생활 문제 해결 프로젝트들입니다.</p>
<p style="color: #6b7280; font-size: 1.1rem; line-height: 1.6; max-width: 800px; margin: 1rem auto 0;">각 프로젝트는 실제 사용자의 문제를 해결하고, 사회적 가치를 창출하는 것을 목표로 합니다.</p>
</div>