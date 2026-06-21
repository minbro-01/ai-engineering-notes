# AI Engineering Study

학과 수업에서 배운 AI Engineering 관련 개념을 정리하고, 필요한 경우 작은 구현 연습으로 연결하는 학습 기록 저장소입니다.

이 저장소의 목적은 프로젝트 결과물을 모으는 것이 아니라, 수업에서 배운 내용을 내 언어로 다시 정리하고 직접 찾아본 자료와 구현 아이디어를 함께 쌓는 것입니다. 완성도 있는 프로젝트 결과물은 별도의 [`academic-projects`](https://github.com/minbro-01/academic-projects) 저장소에 정리하는 구조로 운영합니다.

## Study Map

| Area | Scope | Repository role |
| --- | --- | --- |
| Data Structures & Algorithms | 리스트, 큐, 스택, 힙, 트리와 알고리즘 구현 연습 | 구현 기초와 문제 풀이 기록 |
| Time Series Analysis | 통계 기반 시계열 분석부터 RNN 기반 모델까지 | 시계열 예측 개념과 모델 비교 |
| Machine Learning | 지도/비지도 학습, 수학적 근거, 모델 작동 원리 | Linear model부터 SVM까지 직접 구현하며 이해 |
| Deep Learning | RNN, CNN, Attention, Transformer | 모델 구조와 구현 아이디어 정리 |
| Natural Language Processing | 기본 NLP부터 LLM까지 | 텍스트 처리, 모델 구조, 정책 제안 프로젝트 배경 정리 |
| Reinforcement Learning | MDP, DP, TD, Q-learning, SARSA, Deep RL | 의사결정 문제와 학습 알고리즘 정리 |
| Computer Vision | 이미지 처리, 인식 모델, 자율주행 인지 | CV 개념과 자율주행 인지 프로젝트 배경 정리 |

## Repository Structure

```text
ai-engineering-study/
├─ README.md
├─ coursework/
│  ├─ README.md
│  ├─ data-structures-algorithms/
│  ├─ time-series-analysis/
│  ├─ machine-learning/
│  ├─ deep-learning/
│  ├─ natural-language-processing/
│  ├─ reinforcement-learning/
│  └─ computer-vision/
├─ paper-reviews/
├─ implementations/
├─ notes/
├─ references/
└─ .gitignore
```

## How This Repository Is Organized

| Section | Purpose |
| --- | --- |
| `coursework/` | 학과 수업에서 배운 개념을 정리합니다. |
| `paper-reviews/` | 수업과 관련해 직접 찾아본 논문, 기술 글, 자료를 읽고 요약합니다. |
| `implementations/` | 개념을 이해하기 위한 작은 구현 연습을 남깁니다. |
| `notes/` | 수업과 프로젝트를 넘나드는 일반 개념 노트입니다. |
| `references/` | 강의, 문서, 논문, 글 등 참고 자료를 모읍니다. |

## Related Project Repository

| Repository | Role |
| --- | --- |
| [`academic-projects`](https://github.com/minbro-01/academic-projects) | 차량 궤적예측, DRT 정책 제안, road topology & ego-lane inference 같은 프로젝트 결과물을 정리할 전용 저장소입니다. |

## Study Workflow

```text
coursework -> notes -> paper review -> small implementation -> project repository
```

## Source Policy

- 강의자료나 외부 저장소 내용을 그대로 복사하지 않습니다.
- 참고한 자료는 `references/` 또는 관련 노트에 출처를 남깁니다.
- README와 노트는 내가 이해한 방식으로 다시 설명합니다.
- 구현 파일은 직접 작성한 코드와 참고한 코드를 명확히 구분합니다.

## Current Status

3개 레포 구조에 맞춰 학습 기록 중심으로 재정리한 상태입니다.
