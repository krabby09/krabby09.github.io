---
widget: map
headless: false
active: true
weight: 30     # 홈에서 표시 순서 (intro=10, portfolio=20 다음에 나오게)
title: "오시는 길"
content:
  provider: google       # or "osm" (API키 없이 쓰고 싶으면 osm)
  api_key: ""            # Google Maps 키가 있으면 넣어도 됨 (없어도 렌더됨)
  center:
    latitude: 35.8460    # 전북대 좌표
    longitude: 127.1290
  zoom: 15
  height: 400
  markers:
    - title: "전북대학교"
      latitude: 35.8460
      longitude: 127.1290
---