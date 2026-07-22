# 프라이빗 노천탕 홈페이지

HTML, CSS, JavaScript로 만든 Cloudflare Pages용 정적 홈페이지입니다.

## 폴더 구조

```text
private-openair-spa-cloudflare/
├── index.html
├── css/style.css
├── js/main.js
└── images/
```

## 내용 변경

- `index.html`에서 `[입력]` 표시를 검색해 상호, 가격, 운영시간, 주소, 연락처를 교체합니다.
- `[예약 링크 입력]`은 네이버 예약 등 실제 예약 주소로 교체합니다.
- 사진은 `images` 폴더에 넣고 `index.html`의 플레이스홀더를 `<img>` 요소로 교체합니다.

## Cloudflare Pages 설정

- Framework preset: `None`
- Production branch: `main`
- Build command: 비워두기
- Build output directory: `/`

GitHub 저장소에 이 폴더의 내용 전체를 업로드한 후 Cloudflare Pages에서 저장소를 연결하면 됩니다.
