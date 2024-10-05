---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: project
      text: It's a project I did during my school class.
  - block: slider
    content:
      slides:
      - title: Visualize data
        content: 'Use jupyter notebook and python'
        align: center
        background:
          image:
            filename: image1.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: kaggle activity
        content: Artificial Intelligence with kaggle
        align: center
        background:
          image:
            filename: image2.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Titanic
        content: 'Analysis of data using Titanic data during the kaggle'
        align: center
        background:
          image:
            filename: image3.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  
---