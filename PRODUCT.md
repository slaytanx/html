# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary users are adult children and family caregivers comparing hospitals and calling admissions desks on behalf of an 80s mother recovering from lumbar stenosis surgery, alongside an elderly father commuting by public transit from Gupabal Station who may also browse the guide lightly.

## Product Purpose

Help a family decide which rehabilitation, general, or Korean medicine hospital best fits post-lumbar surgery gait recovery without private indemnity insurance (`실비보험 없음`), balancing public-transit commute fatigue from Gupabal, integrated nursing care (`간호·간병통합서비스`) availability to avoid private caregiver costs, 2026 Stage-3 recovery hospital (`제3기 회복기 재활의료기관` / `비사용증후군`) eligibility, estimated monthly multi-bed ward out-of-pocket costs, and verified review pros/cons.

## Positioning

Unlike generic hospital directories or map listings, every candidate is pre-filtered around four family-specific constraints (Gupabal 3-line subway 5–30 min or direct buses 7722/7211, no private caregiver via integrated wards, non-covered fee risks for uninsured patients, and real pros/cons plus admission phone scripts).

## Operating Context

Caregivers compare options across desktop and mobile, filter by insurance/care type (`간호·간병통합`, `제3기 회복기`, `한방병원`, `3호선 무환승`) or search by station/bus/name, inspect detailed hospital pros/cons, and review the 4 pre-admission phone checklist questions when calling surgical doctors or hospital admissions desks.

## Capabilities and Constraints

- Single self-contained HTML artifact (`rehab-guide.html`, linked from `index.html` and hosted via GitHub Pages).
- Preserve all 10 profiled hospitals (Group A: 6 integrated-care hospitals; Group B: 4 transit-accessible Korean medicine hospitals), 2 borderline transit notes (`원당연세병원`, `명지병원`), 5 excluded hospitals, 4 checklist disclosure items, all official website links, and all phone numbers verbatim.
- Preserve working client-side category filtering, keyword search, empty-state reset, and checklist expand/collapse interactions.
- Eliminate nested bordered boxes inside hospital detail cards and prioritize fast visual scanning across dense cost, transit, and pros/cons metadata.

## Evidence on Hand

Complete factual dataset embedded inside `rehab-guide.html`: 10 hospital profiles, 9 external hospital homepage links, 2026 Stage-3 recovery and integrated nursing care policy summary, comparative 10-row matrix, 5 excluded hospitals with transit times, and 4 phone-call checklist items.

## Product Principles

1. Scannability over ornament: caregivers comparing costs, transit times, and warnings across 10 hospitals need clear typographic and structural hierarchy without nested card clutter.
2. Honest policy framing first: distinguish integrated nursing wards from Korean medicine hospitals upfront before price comparisons create false expectations.
3. Preserve direct action paths: phone numbers, transit lines, and admission checklist questions must remain effortless to locate on both desktop and mobile.

## Accessibility & Inclusion

- Readable body typography, clear contrast, and uncrowded mobile layouts so both adult children and an elderly father can read comfortably without horizontal scrolling or visual fatigue.
- Full keyboard accessibility (`:focus-visible`, skip link, native `<details>` disclosures, `aria-pressed` filter state, `aria-live` result counts).
