# french-study

B1→B2 프랑스어 자기주도 학습 시스템. Claude가 인터랙티브 HTML 연습지를 만들고, 학습자가 답을 제출하면 recast 피드백을 주고, 그 결과가 다음 연습지에 반영된다.

## 구조

| 경로 | 내용 |
|---|---|
| `docs/prd.md` | 학습 설계·소재 정책·운영 루프 (무엇을 왜 배우는가) |
| `docs/worksheet-format.md` | 연습지 HTML 공통 규격 (연습지를 어떻게 만드는가) |
| `docs/feedback-loop.md` | 답변·피드백을 다음 세트로 넘기는 지속 구조 (결과를 어떻게 순환시키는가) |
| `carryover.md` | **살아있는 학습 상태판.** 다음 세트 제작 전 필독, 매 피드백 후 갱신 |
| `log/S{NNN}.md` | 회차별 제출 원문 + 피드백 아카이브 (`log/_TEMPLATE.md` 골격) |
| `worksheet/` | 완성된 연습지 HTML 세트 |

## 루프

`제작(← carryover 읽기) → 학습 → 제출(copyAll) → 피드백(recast) → 기록(log 추가 + carryover 갱신 + 커밋)`

상세는 `docs/feedback-loop.md`.
