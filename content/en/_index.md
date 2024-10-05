---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - widget: about.avatar
  # Introduction section
  - block: features
    content:
      title: <span style="font-size:70%">Brief Introduction</span>
      text: <br><span style="font-size:125%">I am a 3rd-year Statistics student at Jeonbuk National University, also double majoring in Computer Engineering.</span> <br><br>
    design:
      columns: '3'
    

  # Slider section
  - block: slider
    content:
      slides:
      - title: <span style="font-size:80%">Data Visualization</span>
        content: <span style="font-size:80%">Using Jupyter Notebook and Python</span>
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.6
          position: center
          color: '#333'
      - title: <span style="font-size:80%">Kaggle Activities</span>
        content: <span style="font-size:80%">Utilizing AI on Kaggle</span>
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.6
          position: right
          color: '#666'
      - title: <span style="font-size:80%">Titanic</span>
        content: <span style="font-size:80%">Analyzing Titanic data using Kaggle</span>
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

  # Portfolio section
  - block: portfolio
    content:
      title: 'Projects'
      subtitle: 'These are projects conducted during school lessons.'
      page_type: project
      filter_button:
        - name: All
          tag: '*'
        - name: First
          tag: ML
        - name: Second
          tag: RA
        - name: Third
          tag: AL
    design:
      columns: '3'
      view: masonry
      flip_alt_rows: true
      spacing: {padding: [0, 0, 0, 0]}

  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Areas of Interest</span>
      text: These are the areas I am interested in.<br><br><br><br>
      items:
        - name: Web Development
          icon: laptop
          icon_pack: fas
        
        - name: Game Statistics
          icon: gamepad
          icon_pack: fas
          description:  <span style="font-size:90%">Analyzing League of Legends match data</span><br><br>
        - name: YouTube
          icon: youtube
          icon_pack: fab
          description:  <span style="font-size:90%">Keeping up with the latest trends</span><br><br>

        - name: Apple
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">Exploring trends in Apple stocks</span><br><br>
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
