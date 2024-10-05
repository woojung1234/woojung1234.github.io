---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: '프로젝트'
subtitle: '학교 수업 중 진행한 것입니다.'

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
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
---

{{< slider >}}
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
{{< /slider >}}
