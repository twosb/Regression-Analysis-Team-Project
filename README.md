# Regression-Analysis-Team-Project
```Kaggle Data : Zillow’s Home Value Prediction를 사용한 회귀분석 프로젝트```
</br>

<img src="readme_img/title.png" width="700" align="center">
<img src="readme_img/description.png" width="700" align="center">
</br>

## [ 팀프로젝트 활동 로그 ]
### EDA
- *2018/06/19 (화)*
	- 이전까지 각자 진행했던 EDA를 공유
	- missing ratio가 80% 이상인 피처를 처리하기 하기 위해 각자의 분석 할당량 분할

- *2018/06/20 (수)*
	- 각자 맡은 피처를 분석한 내용을 브리핑하고, 해당 피처 제거 여부와 NaN 값 처리에 대해 토론<br/>
    	➜ missing ratio가 80% 이상되면 종속변수를 알아내는데 영향이 미미할 것으로 보고 모두 제거하기로 하였음
    
    - missing ratio가 30%보다 크고 80% 보다 작은 값을 갖는 피처을 어떻게 처리할지 토론<br/>
    	➜ 각 피처들을 분석해보았을때, 대부분 missing ratio가 높고 중요도가 높지 않다고 생각되어, 대부분 제거하기로 하였지만,<br/>몇몇 피처들은 좀 더 확인해 볼 필요가 있다고 판단되어 기록해두었다가 추후 재검토하기로 하였음
	
    - missing value가 30% 미만에 해당하는 25개의 피처 분석에 대해 토론<br/>
        ➜ 25개 중 단 2개의 피처만이 약 9%의 missing ratio를 갖고 나머지 피처들은 모두 4% 미만의 피처이므로,<br/>회귀분석에 있어서 주요 피처가 될 가능성이 높다고 판단되어 모든 피처를 다 함께 면밀히 EDA를 진행하고 토론하기로 하였음 
  
- *2018/06/23 (토)*
	- missing value가 30% 미만에 해당하는 피처를 각자 분석한 결과를 브리핑<br/>
    	➜ 3일이라는 시간이 있었지만 피처수가 많기도 하고 매일 수업도 있어서 결국 8개 정도 씩 분석을 했지만 큰 진전은 없었기 때문에 피처들을 비슷한 성격을 갖는 것 끼리 묶고 나눠서 다시 분석하여 2일 후에 브리핑하기로 하였음
  
- *2018/06/25 (월)*
  - 유틸 / 건물타입&위치 / 면적&세금 세가지로 카테고리화한 피처들을 분석한 내용을 공유<br/>
     ➜ 유틸(상범): 집의 유틸리티에 해당하는 변수들(화장실과 방 개수, 건축연도, 수영장 보유 여부)의 히스토그램 분포와 로그 에러 간의 상관관계 분석


	➜ 건물타입&위치(혜신): 집의 지리적 위치와 주소를 나타내는 변수들의 분포와 로그 에러와의 상관관계를 살펴보고, 비슷하거나 같은 정보를 담고 있는 변수들을 탐색함. 특히 지역을 나타내는 코드로 이루어진 변수들을 조작하여 새로운 변수로 만드는 방법에 대하여 고민함


	➜ 면적&세금(원철): 변수들과 logerror와의 상관관계를 살펴보고 중요한 피처들을 확인할 수 있었는데 의미상 상하위의 관계를 갖는 변수들이 있어서 변수들간의 상관관계를 더 살펴보기로 함

- *2018/06/29 (금)*
	- 팀원들의 현재까지의 작업물을 TeamResult.ipynb에 종합하기 위해 각자의 작업을 정리

- *2018/06/30 (토)*
	- 각자 정리한 현재까지의 작업물을 TeamResult.ipynb에 종합하기 위해 GitHub에 각각의 TeamResult.ipynb의 버전으로 push