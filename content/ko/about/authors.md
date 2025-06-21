---
# Display name - YAML 호환 형식으로 수정
title: 김우중

# Is this the primary user of the site?
superuser: true

# Role/position - 4학년으로 수정
role: '전북대학교 통계학과 4학년, 컴퓨터공학 복수전공'

# Status emoji - 개발자 이모지
status:
  icon: 💻

# Short bio
bio: AI와 데이터를 활용한 실생활 문제 해결에 특화된 개발자

# 전문적인 관심사
interests:
- 생성형 AI 활용
- 웹 개발 (React, Node.js)
- 데이터 분석 및 시각화
- 모바일 앱 개발

# Social/Academic Networking
social:
  - icon: github
    icon_pack: fab
    link: https://github.com/woojung1234
  - icon: envelope
    icon_pack: fas
    link: mailto:woojung.dev@gmail.com

---

<style>
/* 이름 색상 강제 적용 - 다크모드에서 하얀색, 라이트모드에서 어두운색 */
.user-name, .author-name, h1.author-name {
  color: white !important;
}

/* 다크모드 전용 */
@media (prefers-color-scheme: dark) {
  .user-name, .author-name, h1.author-name {
    color: white !important;
  }
}

/* 라이트모드 전용 */
@media (prefers-color-scheme: light) {
  .user-name, .author-name, h1.author-name {
    color: #1f2937 !important;
  }
}

/* Hugo 테마의 기본 스타일 덮어쓰기 */
.avatar-wrapper + h1,
.superuser h1,
div[itemtype="https://schema.org/Person"] h1 {
  color: white !important;
}
</style>

<div style="color: var(--bs-body-color, #374151); line-height: 1.6;">

<h1 class="author-name" style="color: white !important; font-size: 2.5rem; font-weight: 700; margin-bottom: 1rem; text-shadow: 0 0 10px rgba(255,255,255,0.3);">김우중</h1>

**전북대학교 통계학과 4학년**이며 **컴퓨터공학을 복수전공**하고 있는 김우중입니다.

**AI와 데이터 기술을 활용한 실생활 문제 해결**에 특화된 개발자를 목표로 하고 있으며, 다음과 같은 프로젝트들을 진행해왔습니다:

### 🚀 주요 프로젝트
- **생성형 AI 여행지 추천 시스템**: GPT API를 활용한 개인맞춤형 여행 플래너
- **Flavor Diffusion 페어링 서비스**: 머신러닝 기반 술과 음식 매칭 서비스  
- **복지서비스 통합 가계부 앱**: 개인 맞춤형 복지서비스와 가계 관리 통합 솔루션

### 💻 기술 스택
- **Frontend**: React, JavaScript, HTML/CSS, Tailwind CSS
- **Backend**: Node.js, Express, MongoDB, MySQL
- **AI/ML**: Python, TensorFlow, OpenAI API, Langchain
- **Mobile**: React Native, Expo, Firebase

### 📊 자격증 및 성과
- **SQLD** (SQL 개발자) 자격증 취득
- **정보처리기사** 필기 합격
- 다수의 **AI 기반 웹/앱 서비스** 개발 경험

</div>

---

<div style="text-align: center; margin: 2rem 0;">
<a href="/ko/project/" style="display: inline-block; background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%); color: white; padding: 12px 24px; border-radius: 8px; text-decoration: none; font-weight: 600; box-shadow: 0 4px 15px rgba(99, 102, 241, 0.3); transition: all 0.3s ease;">
🚀 프로젝트 포트폴리오 보기
</a>
</div>

<script>
// JavaScript로 이름 색상 강제 변경
document.addEventListener('DOMContentLoaded', function() {
  // 모든 가능한 이름 요소 찾기
  const nameSelectors = [
    'h1.author-name',
    '.avatar-wrapper + h1',
    '.superuser h1', 
    'div[itemtype="https://schema.org/Person"] h1',
    '.about-author h1',
    '.author-header h1'
  ];
  
  nameSelectors.forEach(selector => {
    const elements = document.querySelectorAll(selector);
    elements.forEach(el => {
      el.style.color = 'white';
      el.style.setProperty('color', 'white', 'important');
    });
  });
  
  // 혹시 다른 방법으로 생성된 이름 요소도 찾기
  const allH1s = document.querySelectorAll('h1');
  allH1s.forEach(h1 => {
    if (h1.textContent.includes('김우중')) {
      h1.style.color = 'white';
      h1.style.setProperty('color', 'white', 'important');
    }
  });
});
</script>