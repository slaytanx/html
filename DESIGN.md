---
name: 구파발 통원 재활 진료 바인더 (Post-Op Discharge Binder)
description: 차분한 분필빛 지면 위에 딥 틸과 호박색 구분, 1px 진료 인덱스 규격선으로 구성한 한국어 의료 비교 문서 시스템.
colors:
  bg-page: "#f7f8fa"
  bg-surface: "#ffffff"
  bg-raised: "#eef2f6"
  bg-subtle: "#f1f5f9"
  text-primary: "#1a222b"
  text-secondary: "#3b4754"
  text-muted: "#5a6776"
  line: "#dde3ea"
  line-strong: "#c5ced8"
  primary: "#0f766e"
  primary-hover: "#0d5e57"
  primary-soft: "#f0fdfa"
  primary-line: "#99f6e4"
  caution: "#b45309"
  caution-soft: "#fffbeb"
  caution-line: "#fde68a"
  danger: "#b91c1c"
  danger-soft: "#fef2f2"
typography:
  display:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "clamp(26px, 3vw, 38px)"
    fontWeight: 800
    lineHeight: 1.24
    letterSpacing: "-0.03em"
  heading:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "clamp(21px, 2.1vw, 26px)"
    fontWeight: 800
    lineHeight: 1.3
    letterSpacing: "-0.025em"
  card-title:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "20px"
    fontWeight: 800
    lineHeight: 1.3
  marker:
    fontFamily: '"IBM Plex Mono", ui-monospace, "SFMono-Regular", Menlo, Consolas, monospace'
    fontSize: "18px"
    fontWeight: 600
    lineHeight: 1
  group-title:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1.4
  summary-title:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "16.5px"
    fontWeight: 800
    lineHeight: 1.4
  body:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "0em"
  lead:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "15.5px"
    fontWeight: 400
    lineHeight: 1.7
  subhead:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "15px"
    fontWeight: 600
    lineHeight: 1.65
  list:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "14.5px"
    fontWeight: 400
    lineHeight: 1.65
  body-sm:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1.65
  meta:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "13.5px"
    fontWeight: 500
    lineHeight: 1.55
  mono:
    fontFamily: '"IBM Plex Mono", ui-monospace, "SFMono-Regular", Menlo, Consolas, monospace'
    fontSize: "13px"
    fontWeight: 600
    lineHeight: 1.45
    letterSpacing: "0em"
  label:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "12.5px"
    fontWeight: 700
    lineHeight: 1.4
  tag:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "12px"
    fontWeight: 700
    lineHeight: 1.4
  badge:
    fontFamily: '"Pretendard Variable", Pretendard, "Apple SD Gothic Neo", "Malgun Gothic", sans-serif'
    fontSize: "11.5px"
    fontWeight: 700
    lineHeight: 1.4
rounded:
  xs: "2px"
  sm: "6px"
  md: "10px"
  pill: "999px"
spacing:
  section-gap: "52px"
  card-pad: "20px 24px"
  grid-gap: "16px"
components:
  filter-btn:
    backgroundColor: "{colors.bg-surface}"
    textColor: "{colors.text-secondary}"
    rounded: "{rounded.sm}"
    padding: "8px 13px"
  filter-btn-active:
    backgroundColor: "{colors.text-primary}"
    textColor: "{colors.bg-surface}"
    rounded: "{rounded.sm}"
    padding: "8px 13px"
  hospital-card:
    backgroundColor: "{colors.bg-surface}"
    textColor: "{colors.text-primary}"
    rounded: "{rounded.md}"
---

# Design System — Post-Op Discharge Binder

## Overview

70~80대 환자 보호자 및 고령 가족이 진료 비교표를 낮 시간대 데스크톱과 모바일에서 장시간 읽고 전화 문의를 진행할 수 있도록 설계한 **퇴원 수첩 & 진료 기록 바인더** 시각 시스템입니다 (`seed:1c8210f67b5608bf`).
과도한 장식과 중첩 박스를 배제하고, 차분한 분필빛 백지 위에 `1px` 규격선과 의미론적 색상 신호(딥 틸 vs 호박색)만으로 의료 제도 차이를 분명히 드러냅니다.

## Colors

- **Canvas & Surfaces**: 페이지 바탕 `#f7f8fa` (`--bg-page`), 본문 카드 및 시트 `#ffffff` (`--bg-surface`), 표 헤더 및 보조 배경 `#f1f5f9` / `#eef2f6`.
- **Ink Hierarchy**: 본문 제목 및 강조 수치 `#1a222b` (`--text-primary`), 본문 서술 `#3b4754` (`--text-secondary`), 부가 메타 라벨 `#5a6776` (`--text-muted`).
- **Semantic Accents**:
  - **Clinical Teal (`#0f766e`)**: 간호·간병통합서비스, 제3기 회복기 재활의료기관, 장점 포인트, 바인더 활성 인덱스 번호.
  - **Amber Caution (`#b45309`)**: 한방병원(통합간병 미지정), 비급여 추가 주의, 단점·주의 항목.
- **Rules**: 모든 구분선과 테두리는 `#dde3ea` (`--line`) 또는 `#c5ced8` (`--line-strong`)의 `1px solid` 실선만 사용합니다.

## Typography

- **Primary Sans**: `Pretendard Variable` (한글 음절이 단어 중간에 끊기지 않도록 `word-break: keep-all; overflow-wrap: break-word;` 적용).
- **Tabular Mono**: `IBM Plex Mono` (`font-variant-numeric: tabular-nums`)는 병원 인덱스 번호(`01`~`10`), 내비게이션 번호, 전화번호(`.tel`), 비교표 번호에만 제한적으로 적용합니다.
- **Measure**: 히어로 및 섹션 설명 산문은 `64ch~72ch` 폭으로 제한해 가독성을 유지합니다.

## Layout

- **Sticky Binder Bar**: 상단 `56px` 고정 바(`.top-nav`)에 브랜드 마크와 5개 챕터 링크(`01`~`05`)를 배치하고, 모든 앵커 섹션에 `scroll-margin-top: 72px`를 적용합니다.
- **Hero Architecture**: `1.4fr : 1fr` 비대칭 그리드로 좌측 제목·요약·스코프 칩, 우측 4행 `1px` 선정 기준 원장(`.condition-ledger`)을 배치합니다.
- **Container & Breakpoints**: 최대 폭 `1240px` (`calc(100% - 48px)`), `980px` 이하에서 1열 스택 및 수직 경계선 전환, `640px` 이하에서 좌우 여백 `14px` 및 컴팩트 컨트롤 적용.

## Elevation & Depth

- 그림자 남용 대신 표면 색차(`#f7f8fa` vs `#ffffff`)와 `1px` 구분선으로 위계를 만듭니다.
- 카드와 비교표 래퍼에는 최소한의 접지감(`0 1px 2px rgba(26, 34, 43, 0.04)`)만 허용합니다.

## Shapes

- **Radius Scale**: 버튼·입력창·인덱스 배지 `6px`, 카드·표 래퍼·아코디언·알림 상자 `10px`, 상태 태그·스코프 칩 `999px`.

## Components

- **Hospital Detail Record (`.hospital-card`)**: 외곽 단일 카드(`.hospital-card`) 내부에 중첩 박스를 두지 않고, 상단 식별부(번호 탭 `.serial-code` + `h4` + 주소 + 배지 + 우측 연락처) 아래에 `1px` 수직/수평 구분선으로 나뉜 3열 스펙 원장(`.card-meta-grid`)과 2열 후기 원장(`.review-box`)을 직결합니다.
- **Filter & Matrix**: `.filter-btn[aria-pressed="true"]`는 `#1a222b` 솔리드 반전 상태로 활성 상태를 표시하고, 빈 검색 결과 시 빈 그룹 제목(`.cards-group-title`)을 함께 숨기며 `#empty-result` 복구 버튼을 제공합니다.
- **Accordion (`.accordion-stack`)**: `<details>`/`<summary>` 기반 체크리스트와 `CommandEvent`(`--toggle-all`) + 클릭 폴백으로 전체 열기/접기를 지원합니다.

## Do's and Don'ts

- **Do**: 카드 내부 다중 메타 정보나 장단점 비교는 중첩 테두리 상자 대신 `1px solid var(--line)` 분할 격자로 정렬합니다.
- **Do**: `1px` 전체 테두리(`border: 1px solid`)와 미묘한 표면 색차(`#fffbeb`)로 주의 알림을 구분합니다.
- **Don't**: 제목(`h1`~`h4`) 바로 위에 작은 아이브로우(eyebrow/kicker) 텍스트 줄을 놓지 않습니다.
- **Don't**: 카드나 알림 상자 한쪽 측면에 `2px` 이상의 굵은 컬러 포인트 선(`border-left: 4px solid`)을 쓰지 않습니다.
- **Don't**: 병원 상세 카드 안에 또 다른 둥근 테두리 카드(`.meta-panel` 박스화 등)를 중첩하지 않습니다.
