# www.kbhwang.org — 황규백 미술재단 (KB Hwang's Atelier)

Weebly에서 이전한 정적 웹사이트입니다. GitHub Pages로 배포합니다.

## 구성
| 파일 | 페이지 |
|---|---|
| index.html | Home |
| exhibition.html | Exhibition |
| painting.html | Painting |
| mezzotint.html | Mezzotint |
| biography.html | Biography |
| i-am-lucky.html / interview.html / olympic-art-poster.html | Biography 하위 |
| visit-us.html | Visit Us |
| 2021-exhibition.html | 2021 Exhibition (메뉴 숨김) |

- `uploads/` 작품 이미지·배경·PDF (Weebly 원본 경로 유지)
- `_cdn/`, `images/` Weebly 공통 CSS/JS/폰트 사본 (Weebly CDN 의존 제거)
- `CNAME` = www.kbhwang.org, `.nojekyll` 필수(삭제 금지 — `_cdn` 폴더가 무시되지 않도록)
- 원본 URL(`/painting.html` 등)을 그대로 유지해 기존 링크·검색 결과가 이어집니다.
