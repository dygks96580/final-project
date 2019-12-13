데이터선택
----------
나이키X피스마이너스원의 리셀가 가격이 어느정도에 형성되어있는지 확인해보려고 합니다

데이터수집
----------
![1](https://user-images.githubusercontent.com/58128391/70779105-27b39780-1dc7-11ea-8090-f4bba727383e.png)

나이키신발이 활발하게 거래되고있는 카페 나이키매니아에서 데이터를 수집했습니다

데이터수집과정
-------------

먼저 명령프롬프트를 통해 다음 명령을 수행합니다

![2](https://user-images.githubusercontent.com/58128391/70779405-b58f8280-1dc7-11ea-8a9f-f6141c243e4b.png)

그다음 카페에 들어가기 위해서 로그인창으로 이동해줍니다

![3](https://user-images.githubusercontent.com/58128391/70779408-b6281900-1dc7-11ea-9c50-513a20523a5e.png)

로그인을합니다

![4](https://user-images.githubusercontent.com/58128391/70779410-b6281900-1dc7-11ea-9a71-f449b68080fd.png)

원하는 카페로 이동합니다

![5](https://user-images.githubusercontent.com/58128391/70779413-b6281900-1dc7-11ea-8787-e9f5d422a194.png)

가장 최신글인 보드를 검사합니다

![6](https://user-images.githubusercontent.com/58128391/70779415-b6c0af80-1dc7-11ea-9c0a-59f43336bcd1.png)

가장 최신글로 이동합니다

![7](https://user-images.githubusercontent.com/58128391/70779418-b6c0af80-1dc7-11ea-9088-be2d251f39c9.png)

추출하고자 하는 정보고 어떤형태인지 확인합니다

![8](https://user-images.githubusercontent.com/58128391/70779420-b6c0af80-1dc7-11ea-8143-ea19815cabfa.png)

가격만 추출할수없으므로 텍스트 전체를 추출하고 R에서 가격만 추출합니다

![9](https://user-images.githubusercontent.com/58128391/70779422-b6c0af80-1dc7-11ea-9a98-50ee5df5c872.png)

가격으 txt로 저장합니다

![10](https://user-images.githubusercontent.com/58128391/70779424-b7594600-1dc7-11ea-8156-ae5ea51ada3a.png)

Rscript를 저장합니다

![11](https://user-images.githubusercontent.com/58128391/70780976-123f6d00-1dc9-11ea-94fc-4650ff2ca58b.png)

카페글 특성상 판매가 완료되면 가격이 나오지 않기때문에 최신글을 10분마다 계속 추출합니다

추출한값으로 자료분석을 해보았습니다
Min.   :340000  
1st Qu.:460000  
Median :500000  
Mean   :511539  
3rd Qu.:555000  
Max.   :650000  
NA's   :8      

여기서 나오는 결측값은 카페에서 정한 형식대로 게시물을 올리지않았을때 가격이 추출이 안된 경우입니다

히스토그램을 그려보았습니다

![13](https://user-images.githubusercontent.com/58128391/70782621-cab9e080-1dca-11ea-8e56-efebb0c03bab.png)



