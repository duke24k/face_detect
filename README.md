# 얼굴 이미지를 활용한 이성 추천 시스템
PCA를 통해 동양인의 평균얼굴을 구할 수 있다고 했다. 그렇다면 내 이상형의 평균얼굴도 찾을 수 있지 않을까하는 궁금증을 해소하기 위해 시작했다.

## Flow
1. 나의 이상형인 연예인 4명의 사진을 수집
2. OpenCV2를 활용한 이미지 전처리
3. PCA(Eigenface)를 이용한 데이터 차원축소
4. Support Vector Machine 을 이용한 모델링


## Next step
1. 실제로 소셜 데이팅 앱에서 사용가능하려면, 적은 샘플만을 가지고도 분류 할 수 있어야함.
2. 모델의 안정성과 성능을 높이기 위해서 Fisherface 방법으로 시도해 볼 필요성