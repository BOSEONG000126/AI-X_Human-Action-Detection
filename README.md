# 스마트폰 센서 데이터 분석 활용 구상 Project
<img src="https://github.com/BOSEONG000126/AI-X_Project/assets/116350240/8c5c1f5c-aaa9-4006-a5f6-6b2e0c7be83d"  width="800" height="250">


## Members
  * 김보성 (Team Leader)
  * 고도연 
  * 변성호
  * 박민희
  * 진석호


## Introduction
### Background
  + 현대 사회에 반려견의 수요가 늘면서 반려견을 맡길 애견 유치원 , 호텔 등 다양한 서비스가 등장합니다.
  + 반려견의 혼자있는 시간이 늘어남, 의사 소통의 부재로 인한 문제점을 해결하고자 합니다.

### Contribution
  + 반려견과 견주의 의사소통을 편리하게 합니다.
  + 수면 , 활동량 , 휴식량을 측정하고 분석하여 반려견의 스트레스를 감소 시킵니다.
  + 반려견의 분리불안을 해소하여 좀 더 수월한 견주의 외출을 가능하게 합니다.


## Data Set 분석
<img src="https://github.com/BOSEONG000126/AI-X_Project/assets/116350240/a179c2dc-9a2a-4954-b159-9cab67a3dc51"  width="700" height="250">

  + EDA한 dataset의 instance의 수는 5881개 입니다.
  + Lable은 Laying, Standing, Sitting, Walking, Walking_upstairs, Walking_downstairs로 총 6개의 Lable을 가집니다.
  + 가속 센서, 자이로 센서, 각센서에서 특정 기준으로 측정되는 값을 다양한 방식으로 가공한 값을 Feature로 사용하고 있습니다.


<img src="https://github.com/BOSEONG000126/AI-X_Project/assets/116350240/c05ec430-38dc-4afb-815b-d9d934aa274e" width="700" height="350">

  + 각 특징 데이터의 분석을 통하여 각기 행동을 분류 EDA 진행

## Function
<img src="https://github.com/BOSEONG000126/AI-X_Project/assets/116350240/a6c1cb14-e5b1-46b7-8cfc-869ad24fab83" width="700" height="400">

  + 활동량 체크
  + 휴식량 체크
  + 분리불안 감지
  + 수면 패턴 분석


