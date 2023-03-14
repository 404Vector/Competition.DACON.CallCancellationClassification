# Competition.DACON.CallCancellationClassification 
[Competition Link](https://dacon.io/competitions/official/236075)
## 개요
[주제]

통화 데이터로부터 전화해지여부를 예측하는 AI 알고리즘 개발

[설명]

전화 해지여부를 분류하세요.

[주최 / 주관]

데이콘

[기간]

2023년 03월 13일 10:00 ~ 2023년 03월 27일 10:00

## 규칙
1. 평가
평가산식 : Macro F1 Score
Public 평가 : 전체 Test 데이터 100%로 채점


2. 참여 규칙
- 개인으로만 참여 가능
- 개인 참가 방법: 팀 신청 없이, 자유롭게 제출 창에서 제출 가능
 

3. 외부 데이터 및 사전 학습 모델
- 외부 데이터 사용 불가
- 사전 학습 모델(Pre-trained Model) 사용 가능
 

4. 유의 사항
- 1일 최대 제출 횟수: 3회
- 사용 가능 언어: Python, R
- 모델 학습에서 평가 데이터셋 활용(Data Leakage)시 수상 제외
- label encoding, one-hot encoding 시 test 데이터 셋 활용
- data scaling 적용 시 test 데이터 셋 활용
- test 데이터 셋에 pd.get_dummies() 함수 적용
- test 데이터 셋의 결측치 처리 시 test 데이터 셋의 통계 값 활용
- 위 예시 외에도 test 데이터 셋이 모델 학습에 활용되는 경우에 Data leakage에 해당됨
- 최종 순위는 선택된 파일 중에서 채점되므로 참가자는 제출 창에서 자신이 최종적으로 채점 받고 싶은 파일 2개를 선택해야 함
- 대회 직후 공개되는 Public 랭킹은 최종 순위가 아니며 코드 검증 후 수상자가 결정됨
- 데이콘은 부정 제출 행위를 금지하며 데이콘 대회 부정 제출 이력 있을 시 평가 제한 (참조: https://dacon.io/notice/notice/13)
