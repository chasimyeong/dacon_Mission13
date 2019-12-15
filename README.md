# Mission 13. 2019 Jeju BigData Competition - 퇴근시간 버스승차인원예측

https://dacon.io/cpt13/228543

![rank](./image/rank.png)

총 264팀 중 6등을 하였습니다.

내용 : DACON과 제주테크노파크 주관하는 대회로 제주 버스 데이터로 18~20시간대의 승차인원을 예측하는 대회입니다.

팀명 : KIMCHAJANG (3인) / 팀장
#### 최종 264팀중 6등

## 팀 내 역할

### 데이터 분석 프로세스 총괄
-	베이스라인 코딩
-	과거 대회 경험으로 분석기법, 라이브러리 활용 등 시간낭비를 줄이기 위한 리드
-	팀원 알고리즘 효율성 개선

### 베이스라인 코딩
-	정성적 데이터 scoring(종속변수와 그룹평균내어 수치가 작은 것부터 1로 rank를 매김)하여 데이터 전처리
-	datetime 데이터, 평일 주말 나누어 전처리
-	elastic net, Lasso, lightgbm, xgboost 등 주로 사용하는 모델들을 cross-validation을 통한 검증 알고리즘 코딩

### 성능개선을 위한 코딩
-	데이터 정규화를 위한 log화
-	weighted averaging model 사용
-	요일 별 시각화, 변수 상관관계 시각화
-	randomforest, lightgbm, xgboost 모델 튜닝

Framework : colaboratory (Python3)
