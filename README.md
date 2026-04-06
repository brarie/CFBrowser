# CF Problem Browser

Codeforces 문제 브라우저. 단일 HTML 파일로 동작, 설치 불필요.

## 기능

- **문제 필터링** — 난이도(rating), 대회 유형(Div.1/2/3/4, Educational, Global), 문제 인덱스(A~H), 풀이 여부
- **Weekly Goal** — 필터 조건 내 unsolved 문제 중 랜덤으로 N개 픽, 진행도 추적
- **Dashboard** — 실제 CF 레이팅/랭크, XP 시스템(난이도 지수 반영), 연속 솔브 streak, rating별 분포, 최근 7일 활동

## 사용법

1. `index.html` 브라우저로 열기
2. CF 핸들 입력 후 Load
3. 데이터는 1시간 캐시 (Refresh Data로 갱신)

## XP 시스템

첫 AC 기준, 문제 rating에 지수(2.6승)를 적용해 XP 산정. 1800점 문제 대비 2400점 문제는 약 4.5배 XP.
