---
version: 1.1
name: bct-design-system
description: 반도체 장비 부품 위탁 생산 전문기업 ㈜비씨테크(BCT)의 디자인 시스템. 흰 캔버스 위에 BCT 블루(`#1F4E9C`) 단색 계열을 60~70% 쓰고, 짙은 남색(`#153B78`)은 표지·구분·클로징에만, 앰버(`#C98A2B`) 하나를 유일한 포인트 색으로 슬라이드당 1~2곳에만 쓴다. 영문·숫자는 Google Sans, 한글은 Gowun Batang. 구획은 hairline과 여백으로만 한다. 로고는 위아래 블루 바 사이에 BCT 워드마크를 둔 형태로, 단독형과 "(주)비씨테크" 국문 병기형이 있고, 파비콘·프리젠테이션·문서 하단에 쓰는 정사각형 마크가 있다.

colors:
  primary: "#1F4E9C"
  primary-deep: "#153B78"
  primary-deeper: "#0F2C5C"
  primary-pale: "#EAF1FC"
  primary-pale-2: "#F4F8FE"
  on-primary: "#FFFFFF"
  canvas: "#FFFFFF"
  surface: "#F6F9FD"
  ink: "#0B1220"
  steel: "#5B6472"
  steel-soft: "#8A93A3"
  hairline: "#E2E8F3"
  hairline-strong: "#CBD8ED"
  amber: "#C98A2B"
  amber-pale: "#FBE8D3"
  good: "#1F8A5F"
  good-pale: "#E4F3EA"
  risk: "#C1443C"
  risk-pale: "#FBE7E5"
  logo-blue: "#1F4E9C"
  logo-ink: "#1A1A1A"

typography:
  cover-title:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 44px
    pptSize: 40pt
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: 0
  section-number:
    fontFamily: "'Google Sans', sans-serif"
    fontSize: 200px
    pptSize: 150pt
    fontWeight: 700
    lineHeight: 0.9
    letterSpacing: -2px
  section-title:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 40px
    pptSize: 32pt
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  slide-title:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 32px
    pptSize: 26pt
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  slide-subtitle:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 16px
    pptSize: 13pt
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  eyebrow:
    fontFamily: "'Google Sans', sans-serif"
    fontSize: 13px
    pptSize: 11pt
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.12em
    textTransform: uppercase
  card-title:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 18px
    pptSize: 15pt
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: 0
  body:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 16px
    pptSize: 13.5pt
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  table-header:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 14px
    pptSize: 12.5pt
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: 0
  table:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 14px
    pptSize: 12.5pt
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  stat-number:
    fontFamily: "'Google Sans', sans-serif"
    fontSize: 60px
    pptSize: 52pt
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: -1px
  footer:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 12px
    pptSize: 9pt
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: 0.06em
  logo-wordmark:
    fontFamily: "Montserrat ExtraBold"
    note: "로고 파일 안에 아웃라인으로만 존재. 다시 타이핑하지 않는다"
  logo-wordmark-ko:
    fontFamily: "Pretendard Black (재구성)"
    note: "(주)비씨테크 병기. 원래 글꼴 확인 시 교체 예정"

rounded:
  none: 0px
  sm: 9px
  md: 14px
  lg: 18px
  pill: 999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  margin-x: 67px

components:
  hairline-card:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 20px
  value-tile:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    typography: "{typography.card-title}"
    rounded: "{rounded.md}"
    padding: 22px
  stat-card:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.primary-deep}"
    typography: "{typography.stat-number}"
    rounded: "{rounded.lg}"
    padding: 24px
  tag:
    backgroundColor: "{colors.primary-pale}"
    textColor: "{colors.primary}"
    typography: "{typography.eyebrow}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  note-box:
    backgroundColor: "{colors.primary-pale-2}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.sm}"
    padding: 16px 20px
  data-table-header:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.table-header}"
  data-table-row-even:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.table}"
  process-step:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.card-title}"
    rounded: "{rounded.sm}"
    padding: 16px
  process-step-start:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    typography: "{typography.card-title}"
    rounded: "{rounded.sm}"
    padding: 16px
  figure-placeholder:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.steel}"
    typography: "{typography.footer}"
    rounded: "{rounded.md}"
  slide-light:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.slide-title}"
    padding: 0 67px
  slide-dark:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    typography: "{typography.cover-title}"
    padding: 0 67px
  footer-bar:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    typography: "{typography.footer}"
    height: 33px
  window-motif:
    backgroundColor: "{colors.primary-deep}"
    textColor: "{colors.on-primary}"
    rounded: "{rounded.none}"
---

## Overview

㈜비씨테크(BCT)는 반도체 장비 부품 위탁 생산 전문기업이다. 제안서, 회사소개, 기술문서, 작업절차서, 검사성적서, 부적합 보고서처럼 고객사에 내는 자료가 많고, 모두 같은 디자인 언어를 쓴다. 그 출발점은 BCT가 이미 운영하는 웹 시스템(OPS Hub)의 브랜드 언어다. 블루 단색 팔레트, hairline 카드, 둥근 모서리, 그리고 "하나의 창으로 본다"는 window 모티프다.

시스템은 **흰 캔버스**(`{colors.canvas}`) 위에 **BCT 블루**(`{colors.primary}` — `#1F4E9C`) 계열을 한 화면의 60~70%로 쓴다. **짙은 남색**(`{colors.primary-deep}` — `#153B78`)은 표지·구분·클로징 슬라이드 배경과 다크 타일, 푸터 바에 쓴다. 강조는 **앰버**(`{colors.amber}` — `#C98A2B`) 한 가지뿐이고 슬라이드당 1~2곳으로 제한한다. Good·Risk는 표와 체크리스트의 값에만 쓴다.

**Key Characteristics:**
- 흰 캔버스 + BCT 블루 단색 계열 60~70%. 남색은 표지·구분·클로징 전용
- 앰버(`{colors.amber}`)가 유일한 포인트 색. 큰 숫자·핵심 라벨, 슬라이드당 1~2곳
- 그린 계열 강조색은 쓰지 않는다(참고 자료의 그린은 앰버로 대체)
- 영문 알파벳과 숫자는 항상 Google Sans, 한글은 Gowun Batang
- 카드·표는 hairline과 여백으로만 구획. 그림자·좌측 색 띠·제목 밑줄 없음
- 16:9, 좌우 여백 67px(0.7in), 본문 슬라이드 우상단에 BCT 로고, 하단 남색 푸터 바
- 표지·구분·클로징에만 사각형 두 겹의 window 모티프

## Colors

### Brand & Accent
- **BCT Blue** (`{colors.primary}` — `#1F4E9C`): 본문 강조, 아이콘, 표 머리글, eyebrow 번호, 링크. 로고의 바와 워드마크 색과 같다.
- **BCT Blue Deep** (`{colors.primary-deep}` — `#153B78`): 표지·구분·클로징 배경, 다크 카드·밸류 타일, 푸터 바.
- **BCT Blue Deeper** (`{colors.primary-deeper}` — `#0F2C5C`): 표지 배경의 원형 블롭 두 번째 겹. 그라디언트 대신 겹으로 깊이를 낸다.
- **Amber** (`{colors.amber}` — `#C98A2B`): **유일한 포인트 색.** 큰 숫자, 핵심 라벨 1~2곳, 다크 슬라이드의 eyebrow 번호.

### Surface
- **Canvas** (`{colors.canvas}` — `#FFFFFF`): 기본 슬라이드·페이지 배경.
- **Surface** (`{colors.surface}` — `#F6F9FD`): 카드·플레이스홀더 배경, 표의 짝수 행.
- **Blue Pale** (`{colors.primary-pale}` — `#EAF1FC`): 태그·배지 배경, 밝은 강조 영역.
- **Blue Pale 2** (`{colors.primary-pale-2}` — `#F4F8FE`): Note 박스 등 가장 옅은 틴트.
- **Hairline** (`{colors.hairline}` — `#E2E8F3`): 기본 구분선·카드 테두리.
- **Hairline Strong** (`{colors.hairline-strong}` — `#CBD8ED`): 표·통계 카드 테두리.

### Text
- **Ink** (`{colors.ink}` — `#0B1220`): 제목·본문 기본 글자.
- **Steel** (`{colors.steel}` — `#5B6472`): 보조 설명.
- **Steel Soft** (`{colors.steel-soft}` — `#8A93A3`): 캡션, 페이지 태그, 비활성. 장식성 글자에만.
- **On Primary** (`{colors.on-primary}` — `#FFFFFF`): 블루·남색 위 글자.

### Semantic
- **Good** (`{colors.good}` — `#1F8A5F`) / **Good Pale** (`{colors.good-pale}`): 표의 긍정 값(유효·양호) 전용.
- **Risk** (`{colors.risk}` — `#C1443C`) / **Risk Pale** (`{colors.risk-pale}`): 위험·주의 값 전용. 남용 금지.
- **Amber Pale** (`{colors.amber-pale}` — `#FBE8D3`): 앰버 라벨의 옅은 바탕.

### Logo Colors

로고 사용 가이드 v1.0의 값이다.

| 이름 | HEX | RGB | CMYK (인쇄) | 쓰는 곳 |
|---|---|---|---|---|
| BCT Blue | `#1F4E9C` | 31 78 156 | C80 M50 Y0 K39 (임시) | 바, BCT 워드마크 |
| Ink | `#1A1A1A` | 26 26 26 | K90 | (주)비씨테크 |
| Black | `#000000` | 0 0 0 | K100 | 단색(black) 변형 |
| White | `#FFFFFF` | 255 255 255 | 인쇄 안 함 | white 변형 |

BCT Blue의 CMYK는 RGB를 수식으로 환산한 임시값이다. 첫 인쇄 때 인쇄소 교정본으로 확정한다.

### Accessibility Notes

| 조합 | 명도비 | 쓰는 법 |
|---|---|---|
| `{colors.primary}` 글자 / `{colors.canvas}` | 8.0:1 | 본문 링크·강조에 그대로 쓴다 |
| `{colors.on-primary}` 글자 / `{colors.primary-deep}` | 10.9:1 | 다크 슬라이드 본문 |
| `{colors.amber}` 글자 / `{colors.canvas}` | 2.9:1 | 본문 크기 글자로는 기준 미달. 큰 숫자(24px 이상 Bold)·라벨 배경색으로 쓴다 |
| `{colors.amber}` 글자 / `{colors.primary-deep}` | 3.7:1 | 다크 슬라이드의 큰 숫자·eyebrow 번호(Bold)에만 |
| `{colors.steel-soft}` 글자 / `{colors.canvas}` | 3.1:1 | 장식성 캡션·페이지 태그에만. 읽어야 할 정보는 `{colors.steel}`(6.0:1) |

## Typography

### Font Family

- **영문 알파벳과 숫자는 항상 Google Sans.** 제목, 본문, 표, 라벨, eyebrow, 푸터, 페이지 번호 모두 해당한다.
- **한글은 Gowun Batang.**
- 한 문장에 한글과 영문·숫자가 섞이면 글자 종류별로 나눠 각각 위 서체를 쓴다(예: "Heater Module 1개당 4가닥" → `Heater Module 1` Google Sans / `개당 ` Gowun Batang / `4` Google Sans / `가닥` Gowun Batang). 공백·기호는 앞 조각에 붙인다.
- **웹**: `font-family: "Google Sans", "Gowun Batang", sans-serif;` 순서로 지정하면 Google Sans에 한글이 없어서 글자 단위로 자동 전환된다.
- **PPT**: 텍스트 run을 글자 종류별로 나눠 run마다 서체를 지정한다(bct-presentation 스킬의 `split()` 헬퍼).
- JetBrains Mono는 영문·숫자에 쓰지 않는다. 코드 블록을 그대로 보여 줄 때만 예외.

### Hierarchy — Slides (PPT 13.333×7.5in / Web 1280×720)

| Token | PPT | Web | Weight | Use |
|---|---|---|---|---|
| `{typography.cover-title}` | 40pt | 44px | 700 | 표지 제목 |
| `{typography.section-number}` | 150pt | 200px | 700 | 구분 슬라이드 큰 번호 |
| `{typography.section-title}` | 32pt | 40px | 700 | 구분 슬라이드 제목 |
| `{typography.slide-title}` | 26pt | 32px | 700 | 슬라이드 제목 |
| `{typography.slide-subtitle}` | 13pt | 16px | 400 | 부제 |
| `{typography.eyebrow}` | 11pt | 13px | 700 | 섹션 번호 + 영문 대문자 태그 |
| `{typography.card-title}` | 14~16pt | 15~19px | 700 | 카드·타일 제목 |
| `{typography.body}` | 13~13.5pt | 16px | 400 | 본문 |
| `{typography.table-header}` / `{typography.table}` | 12~13pt | 12~15px | 600 / 400 | 표 머리글 / 본문 |
| `{typography.stat-number}` | 48~56pt | 60~64px | 700 | 큰 통계 숫자 |
| `{typography.footer}` | 9~9.5pt | 11~12px | 500 / 700 | 푸터, 페이지 번호 |

**하한선:** 이 표보다 작게 내리지 않는다. 발표 화면 뒷자리에서도 읽혀야 한다는 것이 BCT의 명시적 요구사항이다(본문 13pt 이상, 제목 26pt 이상).

### Logo Typefaces

로고 파일 안에서만 쓰이고, 모두 아웃라인(패스)으로 들어 있다.

- **BCT (영문)**: Montserrat ExtraBold
- **(주)비씨테크 (국문)**: Pretendard Black(재구성). 원본이 PNG뿐이라 원본 글자 상자에 맞춰 다시 그렸다. 원래 글꼴을 확인하면 교체한다.

## Layout

### Slide Grid

- **크기**: PPT 13.333×7.5in(pptxgenjs `LAYOUT_WIDE`) / Web 1280×720px.
- **좌우 여백**: `{spacing.margin-x}`(67px = 0.7in) 고정.
- **헤더**: eyebrow 0.42in → 제목 0.68in → (선택) 부제 1.28in. 본문 슬라이드 우상단에 BCT 로고(높이 0.46in). 제목 상자 폭은 로고와 겹치지 않게 1.05in 줄인다.
- **본문 영역**: 1.5~1.95in에서 6.85in까지.
- **푸터 바**: 높이 0.34in, 남색(`{colors.primary-deep}`) 배경. 왼쪽 BCT 마크(`bct_mark_white`) + BCT, 가운데 문서명(흐리게), 오른쪽 페이지 번호. 다크 슬라이드에서는 채운 바 대신 상단 hairline만.
- 헤더·푸터 높이는 슬라이드 유형과 상관없이 같다.

### Slide Patterns

1. 표지 — 남색, 흰 로고(왼쪽 위), 앰버 키커, 두 줄 제목(둘째 줄 앰버 강조), 인용 한 줄, 원형 블롭 2개, 오른쪽에 내용을 보여 주는 window 모션 그래픽 + 지표 카드 3개, 하단 hairline 푸터(마크)
2. 목차
3. 구분 — 남색, 큰 번호 + 제목
4. 2단 + 밸류 타일
5. 번호 목록
6. 이중 표
7. 프로세스 플로우
8. 이미지 + 불릿
9. 빅 스탯 비교
10. 비교표
11. 클로징 — 남색, 흰 로고

### Spacing System

- **Base unit**: 8px. 구조 여백은 16px(0.16in) 단위.
- **Tokens**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.margin-x}` 67px
- 카드 사이 간격은 14px 이상. 다닥다닥 붙이지 않는다.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 — Flat | 테두리·그림자 없음 | 슬라이드 배경, 밸류 타일, 다크 패널 |
| 1 — Hairline | 1px solid `{colors.hairline}` | 카드, 표, 프로세스 박스 |
| 2 — Hairline Strong | 1px solid `{colors.hairline-strong}` | 통계 카드, 강조 표 |

그림자는 쓰지 않는다. 깊이는 표지의 원형 블롭 두 겹(`{colors.primary-deep}` → `{colors.primary-deeper}`)으로 낸다. 그라디언트는 쓰지 않는다.

### Window Motif

사각형 **두 겹**(바깥 창틀 + 안쪽 창)으로 "하나의 창으로 본다"는 OPS Hub의 개념을 보여 주는 BCT의 시그니처 장식이다. 세 겹 이상 겹치지 않는다. 안쪽 사각형은 바깥 사각형 한 변의 약 60%이고 테두리를 더 밝게 둔다. 표지·구분·클로징 슬라이드의 남색 배경에만 쓰고, 본문 슬라이드에는 쓰지 않는다. 로고가 아니므로 로고 자리에 쓰지 않는다.

## Shapes

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | 슬라이드, window 모티프 |
| `{rounded.sm}` | 9px | Note 박스, 프로세스 박스 |
| `{rounded.md}` | 14px | hairline 카드, 밸류 타일, 플레이스홀더 |
| `{rounded.lg}` | 18px | 통계 카드 |
| `{rounded.pill}` | 999px | 태그·배지 |

## Components

### Labels

**Eyebrow** — 두 자리 섹션 번호(블루 Bold, 다크 슬라이드에서는 앰버) + `/` + 영문 대문자 태그(회색), `{typography.eyebrow}`.

**`tag`** — 배경 `{colors.primary-pale}`, 글자 `{colors.primary}`, `{rounded.pill}`. 통계 카드 상단, 상태 표시.

### Cards & Tiles

**`hairline-card`** — 배경 `{colors.surface}`, 1px `{colors.hairline}`, `{rounded.md}`. 좌측 색 띠·그림자 없음.

**`value-tile`** — 배경 `{colors.primary-deep}`, 흰 글자, 번호는 앰버. 2×2 또는 1×3 그리드.

**`stat-card`** — 1px `{colors.hairline-strong}`, `{rounded.lg}`. 상단 `tag`, 큰 숫자(`{typography.stat-number}`, `{colors.primary-deep}`), 아래에 key-value 행.

**`note-box`** — 배경 `{colors.primary-pale-2}`, `{rounded.sm}`. 보충 설명, 주의사항.

### Data

**데이터 표** — 머리글 행만 `{colors.primary}` 배경 + 흰 글자(`data-table-header`), 본문은 hairline 구분선 + 짝수 행 `{colors.surface}`(`data-table-row-even`). 값 상태는 Good·Risk 글자색으로만.

**프로세스 플로우** — hairline 박스(`process-step`)를 블루 화살표로 잇는다. 시작 박스만 남색으로 채운다(`process-step-start`).

**`figure-placeholder`** — 점선 테두리 + `{colors.surface}` + 원형 아이콘 + `FIG.n — … PLACEHOLDER` 캡션. 최종 납품본에는 남기지 않는다.

### Slide Frame

**`slide-light`** — 흰 배경, 좌우 여백 67px, 우상단 BCT 로고(color), 하단 `footer-bar`.

**`slide-dark`** — 남색 배경, 흰 로고, window 모티프(사각형 두 겹), 원형 블롭 두 개. 표지·구분·클로징 전용. 표지는 오른쪽 window 안에 그 문서의 내용을 보여 주는 모션 그래픽(예: 원가 견적서는 조립 공정과 CT 바)을 둔다.

## Logo

### 구성

위아래 블루 바 사이에 BCT 워드마크를 둔 형태다. 두 가지 형태와 세 가지 색 변형이 있다.

| 형태 | 파일 | 쓰는 곳 |
|---|---|---|
| BCT 단독형 | `bct_logo_BCT_*` (500×201) | 웹, PPT, 장비 라벨, 해외 자료 |
| 국문 병기형 | `bct_logo_BCT_KR_*` (500×289) | 문서 표지, 보고서, 명함, 국내 제출 서류 |
| 마크 | `bct_mark_*` (70×70) | 파비콘, 프리젠테이션·문서 하단(푸터), 아이콘 자리 |

**마크**: BCT 블루 정사각형 안에 한 변 4/7(40/70) 크기의 밝은 정사각형이 들어간 형태다. color는 `#1F4E9C` 바탕 + `#F5F5F5` 안쪽, white는 흰 바탕 + 63% 흰 안쪽. 마크는 window 모티프와 다르다 — 모티프는 테두리만 있는 장식이고, 마크는 채워진 공식 로고다.

| 색 변형 | 쓰는 곳 |
|---|---|
| color | 흰색·밝은 배경(기본) |
| white | BCT 블루·어두운 배경·사진 |
| black | 흑백 인쇄, 팩스, 도장 |

### Clear Space & Minimum Size

- **여백**: 로고 사방에 x 이상. x = BCT 글자 높이의 1/2. 파일은 바 끝에 맞춰 여백 없이 잘려 있으니 배치할 때 여백을 직접 둔다.
- **최소 크기**: 인쇄 단독형 폭 12mm · 병기형 폭 25mm / 화면 단독형 폭 80px · 병기형 폭 160px. 병기형이 최소 크기보다 작아지면 단독형을 쓴다.

### Logo Files

| 파일 | 내용 |
|---|---|
| `logo/bct_logo_BCT_color.svg` / `_white` / `_black` | BCT 단독형 3색 |
| `logo/bct_logo_BCT_KR_color.svg` / `_white` / `_black` | 국문 병기형 3색 |
| `logo/bct_mark_color.svg` / `_white` | 정사각형 마크 2색 (파비콘·푸터) |

원본 관리: `Brand Marketing/Logo_bct/` — `01_SVG_웹용`(SVG), `02_PNG_투명배경`(PNG 2000px), `03_인쇄용_CMYK`(PDF/X-1a, AI, EPS), `src/build_logo.py`(VectorCraft로 전체 재생성). 파일 이름 규칙은 `bct_logo_[BCT|BCT_KR]_[color|white|black]`.

### 금지

- 비율 늘이기·줄이기, 회전·기울이기
- 임의 색 변경, 블루 배경 위에 color 변형
- "BCT"나 "(주)비씨테크"를 서체로 다시 타이핑하기. 항상 로고 파일을 그대로 배치한다
- 최초 로고(기울어진 글자형) 사용. 기존 문서·라벨에 남아 있으면 새 로고로 바꾼다

## Do's and Don'ts

### Do
- 본문 13pt 이상, 제목 26pt 이상을 지킨다
- 영문·숫자는 Google Sans, 한글은 Gowun Batang. 섞인 문장은 글자 종류별로 나눈다
- 앰버는 슬라이드당 1~2곳까지만 쓴다
- 표는 hairline으로만 구획하고, 머리글만 블루 배경
- 여백으로 구조를 표현한다(16px 단위)
- 다크 슬라이드는 표지·구분·클로징에만 쓴다
- 본문 슬라이드 헤더 우상단에 BCT 로고를 둔다

### Don't
- 제목 아래 색 띠·밑줄을 긋지 않는다
- 카드 왼쪽에 색 띠를 넣지 않는다
- 그린 계열 강조색을 쓰지 않는다(BCT의 포인트는 앰버)
- 영문·숫자에 Gowun Batang이나 JetBrains Mono를 쓰지 않는다
- 카드 사이를 14px 미만으로 붙이지 않는다
- window 모티프를 본문 슬라이드나 로고 자리에 쓰지 않고, 사각형을 세 겹 이상 겹치지 않는다
- 로고 글자를 서체로 다시 쓰지 않는다

## Responsive Behavior

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | 슬라이드는 16:9 비율을 유지한 채 폭에 맞춰 축소. 긴 문서(작업절차서 등)는 1열 |
| Tablet | 768–1023px | 카드 그리드 2열. 작업절차서는 Galaxy Tab 가로 화면 기준 |
| Desktop | ≥ 1024px | 슬라이드 1280×720 원본 크기 |

웹 슬라이드는 비율을 지키며 통째로 축소하고, 슬라이드 안 배치를 다시 짜지 않는다.

## Iteration Guide

1. 한 번에 컴포넌트 하나씩 고친다
2. 본문에서는 hex·px 대신 토큰 이름(`{colors.primary}`, `{rounded.md}`, `value-tile`)으로 말한다
3. 새 슬라이드는 위 11가지 패턴에서 먼저 고르고, 정말 다른 구조일 때만 새로 만든다
4. 새 강조가 필요해도 색을 더하지 않는다. 블루 농도와 앰버 한 곳으로 해결한다
5. 로고는 `Brand Marketing/Logo_bct/`의 파일만 쓰고, 고칠 때는 `src/build_logo.py`로 다시 생성한다
6. 같은 토큰을 쓰는 BCT 문서 형식: 프리젠테이션(PPT·웹), 작업절차서(SOP), 케이블 도면, 검사성적서, 부적합(NCM) 보고서, 도면 개정 대조 보고서

> 출처: BCT 로고 사용 가이드 v1.0(2026-10-31, 로고·인쇄), bct-presentation 디자인 가이드 v1.0(2026-08, 색·서체·그리드·컴포넌트·마크), 표지 형식은 `cm_pricing_L3_PRIME_M2_heater.html`. 문서 형식은 getdesign.md의 DESIGN.md 구조를 따랐다.
