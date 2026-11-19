# VR실 프로그램

어린이집 VR실(벽 3면 + 바닥 2면, 적외선 터치) 게임과 도구 모음. swimming 저장소에서 옮겨 옴.

## 폴더

- `vr-tuio-kit/` — 센서(YTS / 고속 트래커) → 브리지 → 게임. 사용법은 `vr-tuio-kit/README.txt`
  - 벽 3면: 과일 베기, 유령 잡기, 슈퍼 골키퍼, 슈퍼 슈터, 무지개 야구왕(1인·2인), 신전 탈출, 숫자 따라쓰기
  - 바닥 2면: 용암 바닥 탈출 (`15_lava_game.bat`)
  - `tracker.py` 고속 트래커, `sim.js` 가짜 터치, `public/operator.html` 관제 화면
- `vr-games/`
  - `MoneyCount_godot/` — 지폐 세기 놀이터 (천 원·오천 원·만 원, Godot 4.3, exe로 내보내기)
  - `종이인형_옷입히기.html`, `털실_목도리뜨기.html` — 웹 판
- `vr360.html` — VR실 360 뷰어 / 화면 감지

## 주의

- `vr-tuio-kit/config.json`, `tracker.json` 에는 VR실 보정값이 들어 있다. VR실 PC에서 업데이트할 때 덮어쓰지 말 것.
