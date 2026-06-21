# AI Engineering Study

AI Engineering을 공부하면서 수업 내용, 논문/자료 리뷰, 구현 실험, 프로젝트 기록을 함께 정리하는 저장소입니다.

목표는 단순히 공부한 내용을 모아두는 것이 아니라, 학과 수업에서 배운 개념을 바탕으로 관련 자료를 더 찾아보고 직접 구현과 실험까지 이어가는 과정을 남기는 것입니다.

> Repository rename note: 이 저장소는 현재 `ai-engineering-notes`로 생성되어 있지만, 방향성은 `ai-engineering-study`에 맞춰 정리하고 있습니다.

## Repository Structure

```text
ai-engineering-study/
├─ README.md
├─ coursework/
│  └─ README.md
├─ paper-reviews/
│  └─ README.md
├─ implementations/
│  └─ README.md
├─ projects/
│  ├─ README.md
│  └─ 01-classification-baseline/
│     ├─ README.md
│     ├─ src/
│     ├─ notebooks/
│     ├─ data/
│     ├─ results/
│     ├─ report.md
│     └─ references.md
├─ experiment-logs/
│  └─ README.md
├─ notes/
│  └─ README.md
├─ references/
│  └─ README.md
└─ .gitignore
```

## How This Repository Is Organized

| Section | Purpose |
| --- | --- |
| `coursework/` | 학과 수업에서 배운 개념을 정리합니다. |
| `paper-reviews/` | 직접 찾아본 논문, 기술 글, 자료를 읽고 요약합니다. |
| `implementations/` | 논문이나 개념을 직접 코드로 구현해본 기록을 남깁니다. |
| `projects/` | 하나의 질문이나 목표를 가진 프로젝트를 폴더 단위로 정리합니다. |
| `experiment-logs/` | 실험 조건, 결과, 실패 원인, 다음 시도를 기록합니다. |
| `notes/` | 프로젝트와 별개로 정리한 AI Engineering 개념 노트입니다. |
| `references/` | 강의, 문서, 논문, 글 등 참고 자료를 모읍니다. |

## Current Projects

| Project | Status | Description |
| --- | --- | --- |
| [`01-classification-baseline`](./projects/01-classification-baseline) | Planned | 분류 문제를 기준으로 데이터 분할, 학습, 평가 흐름을 정리하는 첫 프로젝트입니다. |

## Study Focus

| Topic | What I want to understand |
| --- | --- |
| Data | 데이터 수집, 전처리, 분할, 품질 관리가 모델 성능에 미치는 영향 |
| Model | 모델 구조와 학습 방식이 문제 유형에 따라 달라지는 방식 |
| Training | loss, optimizer, metric, overfitting, validation 흐름 |
| Evaluation | accuracy 외에 실제 문제에서 필요한 평가 기준 |
| Experiment | 실험 조건을 기록하고 결과를 비교하는 방법 |
| Paper to Code | 논문이나 자료에서 읽은 내용을 직접 구현으로 연결하는 방법 |

## Study Workflow

```text
coursework -> notes -> paper review -> implementation -> experiment log -> project report
```

## Current Status

초기 구조를 잡은 상태입니다. 앞으로 수업 기반 학습 기록과 직접 찾아본 자료, 구현 실험을 함께 추가할 예정입니다.
