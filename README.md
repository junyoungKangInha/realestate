# realestate
한국 서울 실거래가 mlops

# data 
최근 5년 서울 (+ 추가적으로 수도권, 경기지역까지 분석하기)

# 참고자료

# 전체 목표
1. 전체 프로젝트 기간은 2달로 한다.
2. ML model 학습보다는 operation 관점에서 진행한다.
3. 주요 프로젝트 아이템은 데이터 기획 / DB 적재 / mlops 설계 (CICD 및 자동 모니터링 시스템)
4. 간단한 부분은 로컬에서 추후 클라우드 셋업까지
5. 사용할 툴은 airflow / docker / mlflow / postgre  ... ++ (AWS)

# 1주차 계획 (25-02-12 ~ 25-02-19)
1. 데이터 기획
2. 데이터 수집

# 1주차 결과 
데이터에 대한 생각 
1. 시군구 번지 단지명 면적/층 중개사소재지 건축년도 등이 들어가 있음
-> 건축사, 즉 브랜드에 대한 정보가 들어가 좋겠다는 생각은 한다.
   하지만, 일단은 프로젝트 목적상 데이터에 대한 추가 분석은 고민을 너무 깊게 하지말자
   (추가 수집가능여부는 파악해보자, 가능한 api 조사)
데이터 기획
  단순하게 실거래가 예측을 하는걸로
Mlops 구상
  1. 매달 api로 실거래가 DB누적관리
  2. 기존 데이터 활용해서 모델링 후 1달치 예측 및 결과 검증
  3. 
# 추후 계획
계획 

4년치 데이터 모델링 
매달 데이터 누적 해서 12개월 치 모니터링 시뮬레이션 시스템 개발

2주 
1. DB구축 + 매달 정기적으로 자동 업데이터 api ( airflow )

2주 
2. mlflow 적용 + 시스템 적용 




   

