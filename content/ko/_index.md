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
      text: <br><span style="font-size:125%">전북대학교 통계학과 4학년이며 컴퓨터 공학을 복수 전공하고 있습니다.</span> <br><span style="font-size:110%">AI와 데이터를 활용한 실생활 문제 해결에 관심이 많습니다.</span> <br><br>
    design:
      columns: '3'
    

  # 슬라이더 섹션
  - block: slider
    content:
      slides:
      - title: <span style="font-size:80%">생성형 AI 여행지 추천</span>
        content: <span style="font-size:80%">https://github.com/gumwoo/travel.git</span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#333'
      - title: <span style="font-size:80%">Flavor Diffusion 페어링</span>
        content: <span style="font-size:80%">https://github.com/woojung1234/ai-pairingsystem.git</span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.6
          position: right
          color: '#666'
      - title: <span style="font-size:80%">복지 + 가계부 앱 금복이</span>
        content: <span style="font-size:80%">https://github.com/gumwoo/donghang_f.git</span>
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
      interval: 3000

  # 포트폴리오 섹션
  - block: portfolio
    content:
      title: '프로젝트'
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

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">핵심 역량</span>
      text: 다양한 기술을 활용해 실제 문제를 해결합니다.<br><br><br><br>
      items:
        - name: 웹 개발 (Web-Development)
          icon: laptop
          icon_pack: fas
        
        - name: 게임 통계
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">league of legends 경기 데이터를 통한 분석</span><br><br>
        - name: 생성형 AI 활용
          icon:  robot
          icon_pack: fab
          description:  <span style="font-size:90%">GPT API, 프롬프트 엔지니어링을 통한 지능형 서비스 개발</span><br><br>

        - name: 풀스택 개발
          icon: code
          icon_pack: fab
          description:  <span style="font-size:90%">프론트엔드부터 백엔드까지 통합 서비스 구현</span><br><br>

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
          description: <span style="font-size:85%">React, javaScript, Tailwind CSS</span><br><br>

        - name: Mobile
          icon: mobile-alt
          icon_pack: fas
          description: <span style="font-size:85%">React Native,Expo go</span><br><br>

        - name: Data Science
          icon: chart-line
          icon_pack: fas
          description: <span style="font-size:85%">Pandas, NumPy, Matplotlib, Seaborn, R</span><br><br>

        - name: Tools & Deployment
          icon: tools
          icon_pack: fas
          description: <span style="font-size:85%">Git, Docker, AWS</span><br><br>
  
  - block: collection
    content:
      id: section-1
      title: 개발 블로그
      subtitle: 프로젝트 진행 과정과 학습 내용을 기록합니다
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - ai-travel
          - flavor-pairing
          - welfare-app
    design:
      columns: '2'
     
---