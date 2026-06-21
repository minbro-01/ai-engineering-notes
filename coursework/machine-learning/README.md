# Machine Learning

지도학습, 비지도학습 모델과 각 모델의 수학적 근거, 작동 원리, 구현 과정을 정리하는 공간입니다.

단순히 라이브러리를 사용하는 것보다 모델이 어떤 가정에서 작동하는지 이해하고, 가능한 범위에서 직접 구현해보는 것을 목표로 합니다.

## Topics

| Topic | What to understand |
| --- | --- |
| Linear Regression | loss, gradient, least squares |
| Logistic Regression | classification, sigmoid, cross entropy |
| Decision Tree | split criterion, entropy, information gain |
| Ensemble | bagging, boosting, random forest |
| SVM | margin, kernel, decision boundary |
| Unsupervised Learning | clustering, dimensionality reduction |

## Implementation Roadmap

| Step | Implementation focus |
| --- | --- |
| 1. Linear model | numpy 기반 linear regression 구현과 gradient descent 확인 |
| 2. Classification baseline | logistic regression과 basic metric 구현 |
| 3. Tree-based model | decision tree의 split rule을 작은 예제로 확인 |
| 4. SVM | margin과 kernel 개념을 수식과 시각화로 정리 |
| 5. Clustering | k-means와 dimensionality reduction의 입력/출력 구조 정리 |

## Study Questions

- 모델이 최적화하는 objective는 무엇인가?
- loss, metric, evaluation은 어떻게 구분되는가?
- 직접 구현한 결과와 scikit-learn 결과가 다를 때 무엇을 확인해야 하는가?
- 모델의 수학적 가정이 실제 데이터에서 깨질 때 어떤 문제가 생기는가?

## Related Repository

완성도 있는 프로젝트 결과물은 [`academic-projects`](https://github.com/minbro-01/academic-projects)에 정리하고, 이곳에는 개념 이해와 작은 구현 연습을 남깁니다.
