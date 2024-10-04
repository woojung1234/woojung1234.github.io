---
title: Map
date: 2024-10-04
---

## 우리 위치

<div id="map" style="height: 400px;"></div>

<script src="https://unpkg.com/leaflet/dist/leaflet.js"></script>
<link rel="stylesheet" href="https://unpkg.com/leaflet/dist/leaflet.css"/>

<script>
  // 지도를 초기화합니다.
  var map = L.map('map').setView([35.846, 127.134], 13); // 위도와 경도를 입력하세요.

  // OpenStreetMap 타일 레이어 추가
  L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
      maxZoom: 19,
      attribution: '© OpenStreetMap'
  }).addTo(map);

  // 마커 추가
  var marker = L.marker([35.846, 127.134]).addTo(map);
  marker.bindPopup('<b>전북대학교</b>').openPopup(); // 팝업 내용
</script>

## 연락처

여기에 연락처 정보를 추가할 수 있습니다.
