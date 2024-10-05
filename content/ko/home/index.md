---
# Homepage
type: widget_page

# Homepage is headless, other widget pages are not.
headless: true

sections:
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

