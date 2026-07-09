<div align="center">

# 유민석 포트폴리오

### 드론 · AI · 웹을 넘나들며 실생활 문제를 기술로 해결합니다

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Design-Responsive-blue)](https://github.com/minseok0326/portfolio)

**[→ 포트폴리오 보기](https://minseok0326.github.io/portfolio)**

</div>

---

## 개요

**벤토 그리드(Bento Grid)** 레이아웃 기반의 개인 포트폴리오 사이트입니다.  
외부 라이브러리 없이 순수 HTML/CSS/JavaScript로 구현했으며, 모바일 반응형을 지원합니다.

---

## 소개

- 드론 전공 + 항공 AI 연구실 학부연구생
- 컴퓨터 비전 기반 프로젝트 (졸음 감지, 불법 주차 탐지) 수행
- 수상: 융복합교과목 성과경진대회 우수상, 창업경진대회 우수상
- 활동: 올림피아드 기체 창작 대회팀, 항공우주 부트캠프, 창업동아리 Swarm Lab, 드론 코더 300

---

## 프로젝트

| 프로젝트 | 기술 | 설명 |
|---------|------|------|
| 조종사 졸음 감지 시스템 | Python, OpenCV, MediaPipe | PERCLOS + 두부 자세 추정 기반 다단계 경고 |
| 청주시 불법 주차 단속 드론 | DJI, Python, OCR | 드론 영상으로 차량 탐지 + 번호판 자동 식별 |
| 버스 길라잡이 | Node.js, Express, HTML/JS | 서울 버스 실시간 위치 + 신호 정보 웹앱 |

---

## 디자인

- **레이아웃:** CSS Grid 12컬럼 벤토 그리드
- **네비게이션:** 고정 상단 바 + 모바일 햄버거 메뉴
- **컬러 시스템:** CSS 변수 기반 (`--navy`, `--accent`, `--bg`)
- **폰트:** Inter + Noto Sans KR (Google Fonts)
- **인터랙션:** 프로젝트 클릭 시 모달 팝업, 호버 트랜지션

---

## 파일 구조

```
portfolio/
├── index.html              # 메인 포트폴리오 (모든 콘텐츠 포함)
├── 증명사진.jpg             # 프로필 이미지
├── bus-preview.png         # 버스 길라잡이 미리보기
├── drone_detection.jpeg    # 드론 불법주차 탐지 이미지
├── drone_flight.jpeg
├── drone_ocr.jpeg
├── drone_stats.jpeg
├── sleep_dataset.jpeg      # 졸음 감지 데이터셋
├── sleep_demo.jpeg
├── sleep_detection.jpeg
├── sleep_graph.jpeg
└── sleep_hardware.jpeg
```

---

## 로컬 실행

별도 빌드 과정 없이 `index.html`을 브라우저에서 바로 열면 됩니다.

```bash
git clone https://github.com/minseok0326/portfolio.git
cd portfolio
# index.html 을 브라우저로 열기
open index.html        # macOS
start index.html       # Windows
```

또는 Live Server (VS Code 확장) 사용 권장.

---

## 연락처

- Email: yuacd0@naver.com
- GitHub: [minseok0326](https://github.com/minseok0326)
