---
# Leave the homepage title empty to use the site title
title:
date: 2025-06-21
type: landing

sections:

  - widget: about.avatar
  # 소개 섹션
  - block: features
    content:
      title: <span style="font-size:70%">자기소개 요약본</span>
      text: <br><span style="font-size:125%">전북대학교 통계학과 4학년이며 컴퓨터 공학을 복수 전공하고 있습니다.</span> <br><span style="font-size:110%">AI와 데이터를 활용한 실생활 문제 해결에 특화된 개발자를 목표로 합니다.</span> <br><br>
    design:
      columns: '3'
    

  # 슬라이더 섹션
  - block: slider
    content:
      slides:
      - title: <span style="font-size:80%">생성형 AI 여행지 추천</span>
        content: <span style="font-size:80%">GPT API를 활용한 개인맞춤형 여행 플래너</span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#333'
      - title: <span style="font-size:80%">Flavor Diffusion 페어링</span>
        content: <span style="font-size:80%">머신러닝 기반 술과 음식 매칭 서비스</span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.6
          position: right
          color: '#666'
      - title: <span style="font-size:80%">복지 + 가계부 앱 금복이</span>
        content: <span style="font-size:80%">개인 맞춤형 복지서비스와 가계 관리 통합 솔루션</span>
        align: center
        background:
          image:
            filename: image3.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#555'
    design:
      slide_height: '350px'
      is_fullscreen: true
      loop: true
      interval: 4000

  # 포트폴리오 섹션
  - block: portfolio
    content:
      title: '프로젝트 포트폴리오'
      subtitle: 'AI와 데이터 기술을 활용한 실생활 문제 해결 프로젝트들'
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
      flip_alt_rows: true
      spacing: {padding: [0, 0, 0, 0]}

  # 핵심 역량 섹션
  - block: features
    id: features
    content:
      title: <span style="font-size:75%">핵심 역량</span>
      text: 통계학적 사고와 컴퓨터공학 지식을 융합하여 실제 문제를 해결합니다.<br><br><br><br>
      items:
        - name: 생성형 AI 활용
          icon: robot
          icon_pack: fas
          description: <span style="font-size:90%">GPT API, 프롬프트 엔지니어링을 통한 지능형 서비스 개발</span><br><br>
        
        - name: 머신러닝 & 데이터분석
          icon: chart-line
          icon_pack: fas
          description: <span style="font-size:90%">Python, R을 활용한 데이터 분석 및 예측 모델링</span><br><br>
        
        - name: 풀스택 웹 개발
          icon: code
          icon_pack: fas
          description: <span style="font-size:90%">프론트엔드부터 백엔드까지 통합 서비스 구현</span><br><br>

        - name: 모바일 앱 개발
          icon: mobile-alt
          icon_pack: fas
          description: <span style="font-size:90%">React Native를 활용한 크로스플랫폼 앱 개발</span><br><br>

  # 기술 스택 섹션
  - block: features
    content:
      title: <span style="font-size:75%">기술 스택</span>
      text: 프로젝트에서 활용하는 주요 기술들입니다.<br><br>
      items:
        - name: AI/ML
          icon: brain
          icon_pack: fas
          description: <span style="font-size:85%">Python, TensorFlow, PyTorch, OpenAI API, Langchain</span><br><br>
        
        - name: Backend
          icon: server
          icon_pack: fas
          description: <span style="font-size:85%">Node.js, Express, MySQL, PostgreSQL, MongoDB</span><br><br>
        
        - name: Frontend
          icon: window-maximize
          icon_pack: fas
          description: <span style="font-size:85%">React, JavaScript, HTML/CSS, Tailwind CSS</span><br><br>

        - name: Mobile
          icon: mobile-alt
          icon_pack: fas
          description: <span style="font-size:85%">React Native, Expo, Firebase</span><br><br>

        - name: Data Science
          icon: chart-bar
          icon_pack: fas
          description: <span style="font-size:85%">Pandas, NumPy, Matplotlib, Seaborn, R, Jupyter</span><br><br>

        - name: DevOps & Tools
          icon: tools
          icon_pack: fas
          description: <span style="font-size:85%">Git, Docker, AWS, Vercel, Hugo</span><br><br>
  
  # 성과 및 경험 섹션
  - block: collection
    content:
      id: section-1
      title: 개발 성과
      subtitle: 프로젝트 성과와 기술 학습 과정을 기록합니다
      text:
      count: 5
      offset: 0
      order: desc
      filters:
        folders:
          - project
          - posts
    design:
      columns: '2'

  # 연락처 섹션
  - block: features
    content:
      title: <span style="font-size:75%">연락처</span>
      text: 프로젝트 협업이나 기술 토론 언제든 환영합니다!<br><br>
      items:
        - name: GitHub
          icon: github
          icon_pack: fab
          description: <span style="font-size:90%">github.com/woojung1234</span><br><br>
        
        - name: Email
          icon: envelope
          icon_pack: fas
          description: <span style="font-size:90%">woojung.dev@gmail.com</span><br><br>
        
        - name: Portfolio
          icon: globe
          icon_pack: fas
          description: <span style="font-size:90%">woojung1234.github.io</span><br><br>
     
---