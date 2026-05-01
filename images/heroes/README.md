# Hero 이미지 폴더

각 서비스 페이지의 메인 hero(상단 배경) 이미지를 여기에 저장하면
CSS가 자동으로 인식해서 hero 배경에 적용합니다.

## 파일 이름 규칙 (이대로 저장하면 자동 적용)

| 파일명 | 사용 페이지 | 권장 이미지 컨셉 |
|---|---|---|
| `airport.jpg` | services/airport.html | 더블린 공항·도착·비행기·게이트 마중 |
| `moving.jpg` | services/moving.html | 이사 박스·MPV에 짐 싣기·IKEA 봉투 |

## 권장 스펙

- **가로 1600px 이상** (1920×1080 권장)
- **가로:세로 = 16:9 ~ 21:9** (가로로 긴 풍경)
- **파일 형식**: `.jpg` 또는 `.webp`
- **파일 크기**: 500KB 이하 (TinyPNG.com이나 Squoosh.app으로 압축)

## 무료 스톡 사이트 추천

이미지를 어디서 찾을까 막막하면 아래 사이트에서 무료로 다운받을 수 있습니다.
모두 상업적 이용 가능, 출처 표기 불필요:

- **Unsplash** — https://unsplash.com (가장 추천. 사진 퀄리티 최고)
- **Pexels** — https://pexels.com
- **Pixabay** — https://pixabay.com

## 검색 키워드

### airport.jpg
- `dublin airport`
- `airport pickup`
- `airport terminal`
- `airport arrival`
- `airplane gate`
- `passenger meeting`

### moving.jpg
- `moving boxes`
- `moving day`
- `ikea bag`
- `moving van`
- `loading car trunk`
- `apartment moving`

## 적용 방법

1. 위 사이트에서 사진 다운로드
2. 파일명을 `airport.jpg` 또는 `moving.jpg`로 변경
3. 이 폴더(`/images/heroes/`)에 저장
4. 끝! — 새로고침하면 자동 반영됩니다

## 다른 페이지의 hero도 바꾸고 싶다면?

다른 페이지의 hero 이미지는 다른 폴더에서 가져옵니다:

| 페이지 | 현재 hero 이미지 위치 |
|---|---|
| 메인 (index.html) | `images/wicklow/lough-tay.jpg` |
| 소개 (about.html) | `photo1.jpg` (루트) |
| 문의 (contact.html) | `images/wicklow/avoca-mills.jpg` |
| 로드트립 (tours.html) | `images/wicklow/glendalough.jpg` |
| 커스텀 (custom.html) | `images/connemara/bog-road.jpg` |

해당 파일을 같은 이름으로 덮어씌우면 자동 적용됩니다.
또는 `styles.css`의 "PER-PAGE HERO BACKGROUNDS" 섹션에서
url() 경로를 바꿔서 다른 이미지로 변경할 수 있습니다.
