# 동화작가 노영희 공식 웹사이트 (`rhoyounghee-website`)

동화작가 노영희(Rho Young-hee)의 공식 아카이브 및 어린이 글쓰기 지도·강연 안내 웹사이트입니다.

## 파일 구성
- `index.html` — 메인 단일 페이지 웹사이트 (모눈종이·색연필 아카이브, 책장, 『괜찮아! 나는 뻥새니까』 연작, 단편 4편 첫 문단, 연보·기록, 글쓰기 지도 문의)
- `robots.txt` — 검색엔진 크롤링 설정
- `sitemap.xml` — 사이트맵
- `노영희_웹사이트_운영대장.md` — 작업 이력, 비공개 원칙, 남은 배포 체크리스트 (Antigravity ↔ Claude 공용 인수인계 문서)

## 배포 전 필수 교체 항목
1. 최종 도메인 확정 후 `index.html`, `robots.txt`, `sitemap.xml` 내 임시 주소 `https://noyounghee.kr/` 일괄 교체
2. `og-image.jpg` (1200×630) 최상위 폴더 추가
3. `index.html` 내 `NAVER_VERIFICATION_CODE` 교체

## 2026-11-24 업데이트

- 첫 화면 원고지 아래 강물 장식 띠와 관련 애니메이션 제거.
- 브랜드의 HD 웹앱 아이콘을 바탕으로 favicon.ico (16/32/48/256px), PNG 파비콘 (32/48px), 고해상도 아이콘 (192/512px), Apple touch icon (180px), 웹 매니페스트 연결.
- 배경음악: 슈만 〈트로이메라이〉, Donald Betts 연주. 퍼블릭 도메인 녹음을 같은 사이트에서 제공하며, 하단 출처와 MUSIC-CREDITS.md에 이용 근거를 보관. 기존 bgm.mp3는 연결하지 않고 원본 보관.
- 브랜드 아이콘 원본: 사용자가 제공한 Google Drive 06_Digital 폴더의 HD_webapp_icon_512.png, HD_webapp_icon_192.png, HD_apple_touch_icon_180.png.
