---
# Leave the homepage title empty to use the site title
title:
date: 2025-06-21
type: landing

sections:

  - widget: about.avatar
  
  # 소개 섹션 - 간결하고 모던한 디자인
  - block: features
    content:
      title: <span style="font-size:75%; color: #2563eb; font-weight: 600;">Profile</span>
      text: <br><span style="font-size:115%; color: #1f2937; line-height: 1.6;">전북대학교 통계학과 4학년이며 컴퓨터 공학을 복수 전공하고 있습니다.</span> <br><span style="font-size:105%; color: #4b5563; line-height: 1.5; margin-top: 8px; display: block;">AI와 데이터를 활용한 실생활 문제 해결에 특화된 개발자를 목표로 합니다.</span> <br><br>
    design:
      columns: '1'
      background:
        color: '#f8fafc'
        gradient_start: '#f8fafc'
        gradient_end: '#ffffff'
      spacing:
        padding: ['60px', '0', '60px', '0']
    

  # 슬라이더 섹션 - 색감 통일 및 깔끔한 디자인
  - block: slider
    content:
      slides:
      - title: <span style="font-size:85%; color: #ffffff; font-weight: 600; text-shadow: 0 2px 4px rgba(0,0,0,0.3);">생성형 AI 여행지 추천</span>
        content: <span style="font-size:75%; color: #f1f5f9; text-shadow: 0 1px 3px rgba(0,0,0,0.4);">GPT API를 활용한 개인맞춤형 여행 플래너</span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.4
          position: center
          color: 'linear-gradient(135deg, #667eea 0%, #764ba2 100%)'
      - title: <span style="font-size:85%; color: #ffffff; font-weight: 600; text-shadow: 0 2px 4px rgba(0,0,0,0.3);">Flavor Diffusion 페어링</span>
        content: <span style="font-size:75%; color: #f1f5f9; text-shadow: 0 1px 3px rgba(0,0,0,0.4);">머신러닝 기반 술과 음식 매칭 서비스</span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.4
          position: center
          color: 'linear-gradient(135deg, #f093fb 0%, #f5576c 100%)'
      - title: <span style="font-size:85%; color: #ffffff; font-weight: 600; text-shadow: 0 2px 4px rgba(0,0,0,0.3);">복지 + 가계부 앱 금복이</span>
        content: <span style="font-size:75%; color: #f1f5f9; text-shadow: 0 1px 3px rgba(0,0,0,0.4);">개인 맞춤형 복지서비스와 가계 관리 통합 솔루션</span>
        align: center
        background:
          image:
            filename: image3.jpg
            filters:
              brightness: 0.4
          position: center
          color: 'linear-gradient(135deg, #4facfe 0%, #00f2fe 100%)'
    design:
      slide_height: '400px'
      is_fullscreen: false
      loop: true
      interval: 5000

  # 포트폴리오 섹션 - 배경과 간격 개선
  - block: portfolio
    content:
      title: '<span style="color: #1f2937; font-weight: 700; font-size: 2.2rem;">프로젝트 포트폴리오</span>'
      subtitle: '<span style="color: #6b7280; font-size: 1.1rem; line-height: 1.6;">AI와 데이터 기술을 활용한 실생활 문제 해결 프로젝트들</span>'
      page_type: project
      filter_button:
        - name: 전체
          tag: '*'
        - name: AI 서비스
          tag: AI
        - name: 웹 개발
          tag: Web
        - name: 모바일 앱
          tag: App
    design:
      columns: '3'
      view: masonry
      flip_alt_rows: false
      background:
        color: '#ffffff'
      spacing:
        padding: ['80px', '0', '80px', '0']

  # 핵심 역량 섹션 - 카드 스타일 개선
  - block: features
    id: features
    content:
      title: <span style="color: #1f2937; font-weight: 700; font-size: 2rem;">핵심 역량</span>
      text: <span style="color: #6b7280; font-size: 1.1rem; line-height: 1.6;">통계학적 사고와 컴퓨터공학 지식을 융합하여 실제 문제를 해결합니다.</span><br><br><br>
      items:
        - name: 생성형 AI 활용
          icon: robot
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">GPT API, 프롬프트 엔지니어링을 통한 지능형 서비스 개발</span><br><br>
        
        - name: 머신러닝 & 데이터분석
          icon: chart-line
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">Python, R을 활용한 데이터 분석 및 예측 모델링</span><br><br>
        
        - name: 풀스택 웹 개발
          icon: code
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">프론트엔드부터 백엔드까지 통합 서비스 구현</span><br><br>

        - name: 모바일 앱 개발
          icon: mobile-alt
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">React Native를 활용한 크로스플랫폼 앱 개발</span><br><br>
    design:
      background:
        color: '#f8fafc'
      spacing:
        padding: ['80px', '0', '80px', '0']

  # 기술 스택 섹션 - 그리드 레이아웃 및 색상 개선
  - block: features
    content:
      title: <span style="color: #1f2937; font-weight: 700; font-size: 2rem;">기술 스택</span>
      text: <span style="color: #6b7280; font-size: 1.1rem; line-height: 1.6;">프로젝트에서 활용하는 주요 기술들입니다.</span><br><br>
      items:
        - name: AI/ML
          icon: brain
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:85%; line-height: 1.5;">Python, TensorFlow, PyTorch, OpenAI API, Langchain</span><br><br>
        
        - name: Backend
          icon: server
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:85%; line-height: 1.5;">Node.js, Express, MySQL, PostgreSQL, MongoDB</span><br><br>
        
        - name: Frontend
          icon: window-maximize
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:85%; line-height: 1.5;">React, JavaScript, HTML/CSS, Tailwind CSS</span><br><br>

        - name: Mobile
          icon: mobile-alt
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:85%; line-height: 1.5;">React Native, Expo, Firebase</span><br><br>

        - name: Data Science
          icon: chart-bar
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:85%; line-height: 1.5;">Pandas, NumPy, Matplotlib, Seaborn, R, Jupyter</span><br><br>

        - name: DevOps & Tools
          icon: tools
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:85%; line-height: 1.5;">Git, Docker, AWS, Vercel, Hugo</span><br><br>
    design:
      background:
        color: '#ffffff'
      spacing:
        padding: ['80px', '0', '80px', '0']
  
  # 연락처 섹션 - 미니멀하고 전문적인 디자인
  - block: features
    content:
      title: <span style="color: #1f2937; font-weight: 700; font-size: 2rem;">연락처</span>
      text: <span style="color: #6b7280; font-size: 1.1rem; line-height: 1.6;">프로젝트 협업이나 기술 토론 언제든 환영합니다!</span><br><br>
      items:
        - name: GitHub
          icon: github
          icon_pack: fab
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">github.com/woojung1234</span><br><br>
        
        - name: Email
          icon: envelope
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">woojung.dev@gmail.com</span><br><br>
        
        - name: Portfolio
          icon: globe
          icon_pack: fas
          description: <span style="color: #4b5563; font-size:90%; line-height: 1.5;">woojung1234.github.io</span><br><br>
    design:
      background:
        color: '#f8fafc'
      spacing:
        padding: ['80px', '0', '100px', '0']
     
---