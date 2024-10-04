---
# An instance of the Contact widget.
# Documentation: https://docs.hugoblox.com/getting-started/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: 마음의 편지
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  # Email form provider
  form:
    provider: netlify
    formspree:
      id:
    netlify:
      # Enable CAPTCHA challenge to reduce spam?
      captcha: false

title: "Contact"
date: 2024-10-04T12:00:00+09:00
draft: false

map:
  provider: 'mapnik'
  zoom: 15
  coordinates:
    latitude: '35.846'  # 위도
    longitude: '127.134'  # 경도      

design:
  columns: '1'
---

{{< map >}}