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
