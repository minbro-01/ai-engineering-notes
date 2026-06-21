# AI Engineering Notes

AI Engineering을 공부하면서 개념, 실험, 프로젝트 기록을 정리하는 저장소입니다.

이 저장소는 단순한 메모장이 아니라, 하나의 주제를 공부할 때 필요한 파일을 프로젝트 단위로 묶어두는 공간으로 구성합니다.

## Repository Structure

```text
ai-engineering-notes/
├─ README.md
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
├─ notes/
└─ references/
```

## How This Repository Is Organized

| Section | Purpose |
| --- | --- |
| `projects/` | 주제별 실험과 구현을 프로젝트 단위로 정리합니다. |
| `notes/` | 프로젝트와 별개로 정리한 AI Engineering 개념 노트입니다. |
| `references/` | 강의, 문서, 논문, 글 등 참고 자료를 모읍니다. |

## Project Folder Rule

각 프로젝트는 아래 구조를 기본으로 사용합니다.

```text
projects/project-name/
├─ README.md      # 프로젝트 목적, 질문, 진행 상태
├─ src/           # 코드
├─ notebooks/     # 실험 노트북
├─ data/          # 데이터 설명 또는 샘플 데이터
├─ results/       # 결과 이미지, 표, 로그
├─ report.md      # 결과 정리
└─ references.md  # 참고 자료
```

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
| Deployment | 학습된 모델을 실제 환경에서 사용하기 위해 고려할 점 |

## Current Status

초기 구조를 잡은 상태입니다. 앞으로 공부한 내용과 실험 결과를 프로젝트 단위로 추가할 예정입니다.
