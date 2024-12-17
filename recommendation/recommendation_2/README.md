# 공정한 추천 알고리즘
추천시스템 벤치마크 데이터셋인 Movielens-1M 데이터를 사용하여 그룹별 선호도 예측 성능을 최대화함과 동시에 공정성 조건을 만족하도록 영화 장르 추천을 하였다.

------------------------------

# 사용방법

+ 데이터셋 : Movielens-1M 

0. test_ml copy.ipynb 실행
   - movielens 데이터세트 전처리, data_combined_new.csv 생성
1. test_unfair.ipynb 실행
   - fair 알고리즘을 적용하지 않은 클러스터링의 성능 예측
2. test_fair.ipynb 실행
   - fair 알고리즘을 적용한 클러스터링의 성능 예측
   - fair 알고리즘 방법 : 모든 가능한 남녀 pair 를 만들고 그룹에 어떤 pair가 들어가야 최적의 성능을 유지할 수 있는지 찾음.

