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

design:
  columns: '1'

  <div id="map" style="height: 400px; width: 100%;"></div>

<script>
  // OpenStreetMap을 기반으로 지도 생성
  var map = L.map('map').setView([{{ .Params.map.coordinates.latitude }}, {{ .Params.map.coordinates.longitude }}], {{ .Params.map.zoom }});

  // 타일 레이어 추가 (OpenStreetMap 타일 서버 사용)
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
    maxZoom: 19,
  }).addTo(map);
</script>

---

