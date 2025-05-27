# Your Own Analysis 1 (Week 1) - 연구 계획

## 주제
**LIN28A binding site predictor using RNA sequence and secondary structure**

본 프로젝트는 RNA-binding protein인 LIN28A의 결합 부위를 예측하는 딥러닝 모델을 제작하는 것을 목표로 합니다.  
논문 ["LIN28A is a suppressor of ER-associated translation in embryonic stem cells"](https://www.sciencedirect.com/science/article/pii/S0092867412012342)의 supplementary CLIP-seq 데이터를 기반으로 실험을 설계합니다.

---

## 배경 및 동기

- LIN28A는 세포 성장과 분화 조절에 중요한 RNA-binding protein입니다.
- 정확한 binding site 예측은 전사 후 조절 메커니즘 이해에 핵심적입니다.
- 기존 연구는 motif 수준에서 제한적이었으며, deep learning을 활용한 정확한 site-level 예측은 부족했습니다.

---

## 연구 목표

- CLIP-seq 기반 LIN28A 결합 위치를 positive sample로 사용
- 동일 transcript 내의 비결합 영역에서 negative sample 구성
- RNAfold를 이용해 2차 구조(dot-bracket) 정보 확보
- Sequence + structure 정보를 CNN 모델의 입력으로 활용
- 모델 평가: AUROC, PR curve, confusion matrix 기반 분석

---

## 주차별 목표 일정

| 주차 | 목표 |
|------|------|
| 1주차 | 연구 주제 및 계획 수립 (YOA1 제출) |
| 2주차 | 데이터 구축, 구조 예측, 전처리 완료 |
| 3주차 | 모델 구성 및 학습, 평가 |

---
