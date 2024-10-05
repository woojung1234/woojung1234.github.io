---
# Homepage
title:
date: 2024-03-25
type: landing

sections:
  # Intro 섹션
  - block: about.avatar
    content:
      author: admin
    headless: true
    weight: 10

  👋 안녕하세요. 김우중입니다. 저는 전북대학교 통계학과 3학년이고, 컴퓨터 공학을 복수 전공하고 있습니다.
  {style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}
  [introduce](https://woojung1234.github.io/ko/about/) 소개는 이쪽에! 😍

  # Portfolio 섹션
  - block: portfolio
    content:
      title: '프로젝트'
      subtitle: '학교 수업 중 진행한 것입니다.'
      page_type: project
      filter_default: 0
      filter_button:
        - name: 전체
          tag: '*'
        - name: 첫번째
          tag: ML
        - name: 두번째
          tag: RA
        - name: 세번째
          tag: AL
    design:
      columns: '1'
      view: masonry
      flip_alt_rows: true
      background: {}
      spacing: {padding: [0, 0, 0, 0]}

  # 슬라이더 섹션
  - block: slider
    content:
      slides:
        - title: 데이터 시각화
          content: 'jupyter notebook과 파이썬 활용'
          align: center
          background:
            image:
              filename: image1.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
        - title: 캐글 활동
          content: 캐글을 활용한 인공지능 활용
          align: center
          background:
            image:
              filename: image2.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: 타이타닉
          content: '캐글 중 타이타닉 데이터를 이용한 데이터 분석'
          align: center
          background:
            image:
              filename: image3.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
    design:
      slide_height: '350px'
      is_fullscreen: true
      loop: true
      interval: 3000
---
