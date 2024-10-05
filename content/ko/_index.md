---
# Leave the homepage title empty to use the site title
title: 
date: 2024-03-25
type: landing

sections:

  # 아바타와 자기소개 섹션
  - block: avatar
    content:
      author: 김우중
      image: 
        filename: avatar.jpg  # 아바타 이미지 파일명
    design:
      align: center  # 중앙 정렬

  # 소개와 링크 추가
  - block: text
    content:
      text: | 
        👋 안녕하세요. 김우중입니다. 저는 전북대학교 통계학과 3학년이고, 컴퓨터 공학을 복수 전공하고 있습니다.
        {style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}
        
        [introduce](https://woojung1234.github.io/ko/about/) 소개는 이쪽에! 😍

  # 소개 섹션
  - block: features
    content:
      title: <span style="font-size:70%">김우중의 포트폴리오</span>
      text: <br><span style="font-size:125%">전북대학교 통계학과 3학년이며 컴퓨터 공학을 복수 전공하고 있습니다.</span> <br><br>
    design:
      columns: '3'
  
  # 슬라이더 섹션
  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">데이터 시각화</span>
        content: <span style="font-size:70%">Jupyter Notebook과 파이썬 활용</span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: <span style="font-size:70%">캐글 활동</span>
        content: <span style="font-size:70%">캐글을 활용한 인공지능 활용</span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: <span style="font-size:70%">타이타닉</span>
        content: <span style="font-size:70%">캐글 중 타이타닉 데이터를 이용한 데이터 분석</span>
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

  # 포트폴리오 섹션
  - block: portfolio
    content:
      title: '프로젝트'
      subtitle: '학교 수업 중 진행한 것입니다.'
      page_type: project
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
      columns: '3'
      view: masonry
      flip_alt_rows: true
      spacing: {padding: [0, 0, 0, 0]}
---
