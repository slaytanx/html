---
version: 1
slug: "rehab-guide-html"
primary_target: "rehab-guide.html"
related_targets: []
---

## Direction contract

- **THESIS**: 70대 중반 여성 복합 외상 퇴원 후 가족 간병인과 어르신이 분필빛 진료 바인더(`#f7f8fa`) 한 권으로 한양방 협진 6곳(딥 틸 `#0f766e`)과 한방 단독 4곳(호박색 `#b45309`)을 오해 없이 대조하고 즉시 전화 문의까지 끝내는 실용 안내서.
- **OWN-WORLD**: 병원 퇴원 수첩과 외래 진료 인덱스 바인더의 시각 세계. 도자기 백색 카드(`#ffffff`)와 차분한 분필 지면(`#f7f8fa`), 1px 규격 구분선(`#dde3ea`), 딥 그래프 잉크(`#1a222b`), `IBM Plex Mono` 고정폭 인덱스(`01`~`10`) 및 전화번호 표기만 사용해 장식적 박스 중첩을 없앤다.
- **STORY**: 56px 고정 바인더 목차에서 시작해 핵심 전략 2트랙 원장(1순위 원내 협진 vs 2순위 한방+별도 정형외과) → 필터·검색 연동 10곳 비교 매트릭스 → 1px 스펙 축선으로 평탄화한 10곳 상세 기록지 → 경계 2곳·제외 5곳 분리 수록 → 전화 문의 필수 4질문 체크리스트로 완결된다.
- **FIRST VIEWPORT**: `assigned.html` 시안 그대로 56px 고정 바인더 툴바 아래 비대칭 2열 히어로(좌측 제목·상황 요약 칩, 우측 A/B 2트랙 전략 원장), 1줄 필터·검색 바, 비교 매트릭스 상단 행이 첫 900px 안에 들어온다.
- **FORM**: `seed:1c8210f67b5608bf` 기반 `Read` 모드 코드 주도 구축(`.impeccable/mocks/decision/assigned.html`). 제목 위 아이브로우(kicker) 금지, 카드 내부 중첩 박스 금지(1px hairline spec ledger로 대체), 1px 초과 좌우 컬러 선 금지, 그라데이션 텍스트 금지, 62–72ch 본문 폭과 표준 HTML 컨트롤을 유지한다.
- **FINISH**: `rehab-guide.html` 단일 파일 완결, 기존 링크 15건·병원 10곳·경계 2곳·제외 5곳·전화 질문 4건·JS 필터/검색/아코디언 원형 보존, `impeccable detect --json` 통과, `agent-browser` 1440×900 & 375×812 검증 후 루트 `DESIGN.md` 작성.
