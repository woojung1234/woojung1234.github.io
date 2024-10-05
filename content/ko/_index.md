---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - widget: about.avatar
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
      - title: <span style="font-size:80%">데이터 시각화</span>
        content: <span style="font-size:80%">Jupyter Notebook과 파이썬 활용</span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#333'
      - title: <span style="font-size:80%">캐글 활동</span>
        content: <span style="font-size:80%">캐글을 활용한 인공지능 활용</span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.6
          position: right
          color: '#666'
      - title: <span style="font-size:80%">타이타닉</span>
        content: <span style="font-size:80%">캐글 중 타이타닉 데이터를 이용한 데이터 분석</span>
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

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">관심분야</span>
      text: 저는 이런 것들에 관심이 있습니다.<br><br><br><br>
      items:
        - name: 웹 개발 (Web-Development)
          icon: laptop
          icon_pack: fas
        
        - name: 게임 통계
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">league of legends 경기 데이터를 통한 분석</span><br><br>
        - name: 유튜브
          icon: youtube
          icon_pack: fab
          description:  <span style="font-size:90%">최신 트렌드 파악</span><br><br>

        - name: 애플 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">애플 주식 경향 트렌드 알아보기</span><br><br>
  - block: collection
    content:
      id: section-1
      title: dreams
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        files:
          - rich
          - web
          - youtube
    design:
      columns: '2' 

---