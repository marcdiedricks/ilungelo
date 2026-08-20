# ILUNGELO — Founding Product Charter

Status: Controlled foundation for MVP v0.1

## Mission
ILUNGELO is an offline-first, mobile-first South African workers' rights companion designed especially for workers who may be marginalized, underserved, underprivileged, multilingual, or operating with limited connectivity and data.

## Core worker journey
UNDERSTAND → CHECK URGENCY → PRESERVE EVIDENCE → UNDERSTAND RIGHTS → FIND THE RIGHT ROUTE → TAKE ONE NEXT ACTION.

## Product principles
- South Africa first.
- Ordinary mobile phones first.
- Offline-capable core journeys.
- Low-bandwidth by design.
- Plain-language and multilingual architecture.
- No compulsory account for basic guidance.
- Worker case data stays local by default.
- AI is optional and must not own authoritative legal rules.
- Consequential rules and deadlines must trace to controlled legal sources.
- Build small, test, pass, freeze.

## Frozen MVP journeys
1. Job loss / dismissal
2. Non-payment / incorrect pay
3. Deductions
4. Working hours / overtime
5. Leave
6. Warning / disciplinary process
7. Workplace unfair treatment

## Architecture boundary
GitHub contains product code, controlled specifications, rules structures, language structures, tests, and release history. Worker case data must not be stored in this repository.

## Build chain
ChatGPT build workflow → GitHub repository → controlled deployment → ILUNGELO PWA → worker device.

## MVP build sequence
B01 Repository Foundation
B02 PWA Shell
B03 Local Data Layer
B04 Offline Engine
B05 Journey Engine
B06 Case Vault
B07 Legal Pack & Source Registry
B08 Rules & Deadline Engine
B09 Evidence + Hours/Pay
B10 Routing Engine
B11 Multilingual Layer
B12 Accessibility
B13 Optional AI Gateway
B14 Privacy & Security Gate
B15 Golden Scenario Testing
B16 Pilot Readiness Freeze

## Golden scenario
The first end-to-end acceptance scenario is a worker reporting: “My boss told me yesterday not to come back.” The core journey must remain useful offline and without AI.

## Scope discipline
No new journey or major feature enters MVP v0.1 without reopening the frozen scope. Implementation follows REQUIREMENT → IMPLEMENTATION → TEST → PASS → FREEZE.
