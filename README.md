## Research
- 학위과정 중 수행한 연구활동

<br>

### GWZINBR의 적용: 서울시 불법주정차를 사례로
#### | 0이 비정상적으로 많이 발생하는 집계구•격자 단위 불법주정차 집계에 GWR의 보완 모델인 GWZINBR을 적용한 연구 
- 도로 위에서만 발생하는 불법주정차의 특성 상 격자, 집계구 등 소규모 공간단위로 집계할 경우 영과잉이 발생한다는 문제점이 존재함
- 이러한 특이점은 일반적인 공간 회귀분석을 적용했을 때 결과가 왜곡될 우려가 있음
- 본 연구에서는 영과잉 공간현상을 위한 회귀 분석 음이항 모형을 적용하여 불법주정차 발생의 영향요인을 분석하고자 함
- 분석 결과, GWZINBR 모형의 수정 결정계수 값이 더 높게 나타남

|<img width="274" height="196" alt="image" src="https://github.com/user-attachments/assets/93fbf424-f86f-4d35-a2e3-5e5f1f1bbde8" />|<img width="630" height="191" alt="image" src="https://github.com/user-attachments/assets/d8c641cc-f6ed-412b-9eb2-b9e77b6f7986" />|
|:---:|:---:|
|영과잉이 발생한 격자 단위 집계|일반 지리가중음이항 모형과의 결과 비교|

<br>

### 고양시 인구이동의 시공간적 패턴 탐색
#### | 시공간큐브와 발생핫스팟 분석으로 고양시의 시공간적 인구 유출입 패턴을 분석한 연구 
- 자연적 인구증가가 둔화된 현재 시점에서 인구이동을 통한 인구 증가는 중요한 인구변동 요인임
- 인구이동은 필연적으로 지역 간의 상호 연결을 유발하고, 동시에 시계열적 특성도 가지고 있음
- 하지만 인구이동에 대한 연구는 최근까지도 고정된 시점에서 단편적으로 이루어지는 경우가 많았음
- 본 연구는 고양시 행정동 단위의 전입•전출 데이터로 시공간 큐브를 생성하고, 발생핫스팟을 도출하여 공간적 군집의 시계열적 변화를 분석하였음
  
|<img width="246" height="240" alt="image" src="https://github.com/user-attachments/assets/aeed02b2-c0bf-4761-9d73-6fe71bec38ee" />|<img width="237" height="219" alt="image" src="https://github.com/user-attachments/assets/72099d9e-8af6-4e7d-8816-11dda60b5dd1" />|
|:---:|:---:|
|발생핫스팟 도출 결과|행정동별 핫스팟 변화|

<br>

### 머신러닝을 이용한 소화용수시설 근처 불법주정차 발생 예측
#### | 머신러닝 분류 알고리즘으로 시간대별 불법주정차 발생 유무를 예측하고 정확도를 비교한 연구
- 기존의 불법주정차 관련 연구는 행위의 원인이나 유발 요인을 탐색하는 연구가 주를 이루었기 때문에, 예측을 시도한 연구는 부족한 실정임
- 본 연구는 강남구를 대상으로 소화용수시설 근처 불법주정차의 발생 여부를 예측하고자 함
- 공간적 변수에 더해 생활인구, 기상 요소 등 시계열적 변수를 추가적으로 독립변수로 활용함
- 여러 머신러닝 분류 알고리즘을 생성하여 비교한 결과, SVM 모형이 가장 높은 정확도를 보임

|<img width="386" height="274" alt="image" src="https://github.com/user-attachments/assets/983ef49c-24e2-4937-adcd-05fd3f0dd228" />|<img width="315" height="115" alt="image" src="https://github.com/user-attachments/assets/c034139c-ab0b-484a-b551-c7528756bf5f" />|
|:---:|:---:|
|소화용수별 예측 결과 분포|예측결과|

<br>

### Does the use of geographic knowledge enhance multilingual text recognition?
#### | 언어별 간판의 비율과 분포가 언어경관의 텍스트 자동인식에 영향을 미치는지 확인한 연구
- 기존의 OCR 모델은 문자 인식에 있어 이미지 자체 정보만을 사용하지만, 본 연구에서는 지역의 언어 분포 정보를 추가적으로 반영했을 때 언어 인식의 정확도가 높아지는지 확인하였음
- 4가지의 가상 분포 패턴을 만들고, EasyOCR로 인식한 사전확률에 직접 라벨링한 실제 언어 분포와 언어별 자기상관 정도를 가중치로 반영하여 인식 정확도를 비교함
- 실제 언어 분포를 가중치로 사용한 모델만으로 모든 가상 패턴에서 충분히 좋은 성능 증가를 보임

|<img width="550" height="377" alt="image" src="https://github.com/user-attachments/assets/f87547d9-5d76-472e-903e-124c2e853318" />|<img width="536" height="155" alt="image" src="https://github.com/user-attachments/assets/cafd54e8-bccf-418a-bb9e-859b97972e6d" />|
|:---:|:---:|
|언어별 실제 분포|가상 분포 패턴|

<br>

### Ethnic segregation on linguistic landscapes
#### | 거리 수준 이미지를 활용해 언어경관의 관점에서 민족 집단 간의 분리 정도를 분석한 연구
- 거리의 언어경관은 민족 집단의 거주지 및 활동 영역을 반영함
- 기존의 인구 집단 분리 현상은 대부분 주거지를 기반으로 분석되었고, 장기적 변화를 포착한 연구가 부족했음
- 본 연구에서는 장기간의 로드뷰 이미지를 활용하여 거리 수준의 시점에서 인구집단의 분리를 분석함
- 거주지 뿐만 아니라 상업지역을 중심으로 발생한 분리 현상도 포착되어, 특정 인구집단이 주로 어디에서 활동하고 소비하는지가 언어경관에 반영됨을 확인함

|<img width="317" height="254" alt="image" src="https://github.com/user-attachments/assets/251b94e2-6064-4c88-b493-03162121baa3" />|<img width="311" height="250" alt="image" src="https://github.com/user-attachments/assets/271b604f-c597-466c-92de-e42e811e63fc" />|<img width="509" height="233" alt="image" src="https://github.com/user-attachments/assets/6cfc18f4-0019-4d00-8251-218bd90a0266" />|
|:---:|:---:|:---:|
|2010년의 중국인 인구와 중국어 간판의 분포|2016년의 분포|거주지와 간판의 분리 수준|


### 공간정보를 활용한 중소기업 기본통계 분석
#### | GIS 와 공간정보를 활용하여 중소기업의 기본 통계를 시각화하고, 밀집지역, 성장•소멸 예상 지역을 분류하는 프로젝트
