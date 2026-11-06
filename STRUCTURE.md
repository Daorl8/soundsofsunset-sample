# STRUCTURE · soundsofsunset-sample (v0.1 · Side A / Side B)

```
soundsofsunset-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인 · 노을 원 인라인 SVG)
├─ wrangler.toml              name = soundsofsunset-sample → soundsofsunset-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ ss-serif.woff2 / ss-serif-italic.woff2   영문 제목 (Instrument Serif, 라틴 + Latin-1)
├─ ss-mono.woff2              라벨 · 트랙 번호 (DM Mono Regular, 라틴)
├─ ss-pretendard.woff2        본문 · 한글 (Pretendard 400–700, 쓰는 글자만)
├─ ss-logo-ink.webp / ss-logo-cream.webp    로고 먹(헤더) · 크림(푸터)
├─ ss-shelf.webp              Tracklist LP 선반
├─ ss-window / ss-turntable .webp           Liner notes (청음석 · 턴테이블)
├─ ss-lamp.webp               Side A 운정
├─ ss-display.webp            Side B 영종도
├─ favicon.png · og-sos.jpg
├─ img/                       다올 제공 원본 19장 (배포 제외)
├─ _old/index_v0.1.1.html     푸터 그라데이션 전 롤백용 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#tracks`(띠색) → `#listen` → `#side-a`(띠색) → `#side-b`(+ `.midnight`) → `#good`(띠색) → 푸터(먹) + 모바일 `.quick`.

## 색 규칙
중성 바탕 · 먹. 노을 #E05625와 그라데이션은 그래픽(노을 원 · 파비콘 · og)과 푸터 면(v0.2)만. 푸터 글자는 어두운 아래쪽에만. 버튼 #C2461B, 작은 주황 글자 #A93E18. 남색 #111A2E는 영종도 심야 띠만.

## 링크
- 운정점: 네이버 `map.naver.com/p/entry/place/2023013289` · 전화 `0507-1358-8250`
- 영종도점: 네이버 `map.naver.com/p/entry/place/2070009392` · 전화 `0507-1364-8251`
- 인스타 `@soundsofsunset_`

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 서브셋 4종 모두 다시(라틴 3종은 U+0020-007E, U+00A0-00FF, U+2013, U+2018-201D, U+2026).
