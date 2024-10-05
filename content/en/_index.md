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
      title: <span style="font-size:70%">A self-introduction summary</span>
      text: <br><span style="font-size:125%">I am a junior majoring in statistics at Chonbuk National University and have a double major in computer engineering.
    </span> <br><br>
    design:
      columns: '3'
    

  # 슬라이더 섹션
  - block: slider
    content:
      slides:
      - title: <span style="font-size:80%">Visualize data</span>
        content: <span style="font-size:80%">Utilize Jupiter Notebook and Python
        </span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#333'
      - title: <span style="font-size:80%">Kaggle activity</span>
        content: <span style="font-size:80%">Artificial Intelligence with Kaggle
        </span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.6
          position: right
          color: '#666'
      - title: <span style="font-size:80%">Titanic</span>
        content: <span style="font-size:80%">Analysis of data using Titanic data during the Kaggle</span>
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
      title: 'Projects'
      subtitle: 'It was done during the school class.'
      page_type: project
      filter_button:
        - name: ALL
          tag: '*'
        - name: 1st
          tag: ML
        - name: 2nd
          tag: RA
        - name: 3rd
          tag: AL
    design:
      columns: '3'
      view: masonry
      flip_alt_rows: true
      spacing: {padding: [0, 0, 0, 0]}

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Interest</span>
      text: I'm interested in these things.<br><br><br><br>
      items:
        - name: Web-Development
          icon: laptop
          icon_pack: fas
        
        - name: Game statistics
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">Analysis from league of legends match data</span><br><br>
        - name: Youtube
          icon: youtube
          icon_pack: fab
          description:  <span style="font-size:90%">Identify the latest trends</span><br><br>

        - name: APPLE
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">Find out Apple Stock Trends</span><br><br>
  - block: collection
    content:
      id: section-1
      title: Dreams
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
  - block: collection
    content:
      title: Experiences
      subtitle:
      text:
      count: 4
      offset: 3
      order: desc
      filters:
        files:
          - highschool
          - millitary
          - jbnu
    design:
      columns: '2' 
     
---