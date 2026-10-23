# 벤치에서 명전까지

정적 HTML/CSS/JavaScript 게임 프로토타입입니다. 화면은 `dist/`에 있으며 별도 패키지 설치가 필요하지 않습니다.

## 로컬 서버 실행

```bash
cd bench-to-hall
python3 -m http.server 4173 --directory dist
```

브라우저에서 `http://localhost:4173`을 엽니다. 서버를 중지하려면 터미널에서 `Control + C`를 누릅니다.

## 구조

- `dist/index.html` — 게임 화면과 선수 생성 UI
- `dist/styles.css` — 반응형 스타일
- `dist/game.js` — 브라우저 저장소 기반 게임 로직
- `backend/API.md` — 실제 서버·DB 구현을 위한 API 계약 초안
