## 지표 설명

### Access

점수산정방식: 

<img width="823" alt="access_01" src="https://github.com/Kyeong6/ParkScore/assets/100195725/18166651-7f99-4c4f-b881-f7352f09af82">


전처리 과정 : [access_data_preprocessing](https://github.com/Kyeong6/ParkScore/blob/main/data_preprocessing/access/parkscore_access.ipynb)

공원의 접근성은 시민들이 공원을 얼마나 쉽게 이용할 수 있는지를 나타내는 중요한 지표이다. 

- 서비스 권역의 범위를 0.75km로 선정한 이유는 "역세권"과 같은 영향력을 미치는 범위에서 자주 사용되는 도보 10분의 개념을 도입하여 도보 10분의 거리인 0.7 ~ 0.8km에 포함되는 0.75km로 선정한 것이다. 이는 시민들이 일상생활에서 공원을 쉽게 접근할 수 있는 거리로 설정한 것이다. </br><br/>

---


### Acreage

평균공원 크기 : 

<img width="323" alt="acreage_01" src="https://github.com/Kyeong6/ParkScore/assets/100195725/35fd33bb-e979-4fd6-9183-0b4be1d883c2">


공원부지 비율 : 

<img width="323" alt="acreage_02" src="https://github.com/Kyeong6/ParkScore/assets/100195725/6c02d5dd-14dc-41d4-8814-776deaa158e5">

1인당 공원면적 :

![image](https://github.com/Kyeong6/ParkScore/assets/100195725/9abc5833-8f1a-4add-acce-6ce5e6693775)

점수산정방식 : 

<img width="374" alt="acreage_03" src="https://github.com/Kyeong6/ParkScore/assets/100195725/bb545e50-c63f-4831-869a-d7041c79f24d">


전처리 과정 : [acreage_data_preprocessing](https://github.com/Kyeong6/ParkScore/blob/main/data_preprocessing/acreage/parkscore_acrege.ipynb)

평균 공원 크기, 공원 부지 비율 및 1인당 공원면적을 고려하여 도시의 녹지 환경을 종합적으로 평가한다.

- 평균 공원 크기 : 평균 공원 크기를 고려함으로써 각 도시의 공원들이 평균적으로 얼마나 큰지를 평가할 수 있으며, 도시에 접근할 수 있는 공원의 크기를 비교할 수 있다.
- 공원 부지 비율 : 공원 부지 비율을 통해 도시면적 대비 공원이 얼마나 차지하는 지를 평가하며, 이는 도시의 환경적 가치를 판단하는 중요한 기준이 된다.
- 1인당 공원면적 :  1인당 공원면적이 클수록 시민들은 더 많은 녹지 공간을 이용할 수 있으며, 이는 도시의 생활 환경을 개선하고 주민의 신체적, 정신적 건강에 긍정적인 영향을 미친다
- 통합평가 : 도시의 녹지 환경인 도시공원의 크기와 도시면적 대비 공원 면적을 모두 고려하여 균형 잡힌 평가를 진행한다. </br><br/>

---

### Investment

점수산정방식 : 

<img width="464" alt="investment_01" src="https://github.com/Kyeong6/ParkScore/assets/100195725/3a13a82b-29dd-4714-ad62-7af8f0e97825">


전처리 과정 : [investment_data_preprocessing](https://github.com/Kyeong6/ParkScore/blob/main/data_preprocessing/investment/README.md)

공원에 대한 투자는 공원의 유지, 관리, 발전 가능성을 나타내는 중요한 지표이다. 100점 만점을 위해서 10,000을 곱하였고 3년 예산안을 사용한 이유는 다음과 같다.

- 연간 변동성 최소화 : 연간 예산의 변동성을 최소화하여 정확한 평가를 가능하게 한다.
- 장기적인 투자 경향 파악 : 장기적인 투자 경향을 파악하여 공원의 지속 가능성을 평가할 수 있다.
- 데이터의 신뢰성 향상 : 장기간의 데이터를 사용하여 평가의 신뢰성을 높인다. </br><br/>

---

### Equity

점수산정방식 : 

<img width="637" alt="equity_01" src="https://github.com/Kyeong6/ParkScore/assets/100195725/621f71d8-52a1-4492-b8ff-fee6c403359a">


전처리 과정 : [equity_data_preprocessing](https://github.com/Kyeong6/ParkScore/blob/main/data_preprocessing/equity/parkscore_equity.ipynb)

도시 공원의 공평한 지리적 분포는 모든 주민이 인종, 소득 수준, 거주지에 관계없이 공원에 접근할 수 있도록 보장하는 것을 목표로 한다.

- Gini 계수 : Gini 계수는 불평등 정도를 측정하는 지표로, 0에서 1사이의 값으로 나타낸다. 값이 0에 가까울수록 자원이 균등하게 분배되고, 1에 가까울수록 불평등이 심하다는 것을 의미한다. 이를 통해 도시 내 도시공원의 지리적 분포가 얼마나 공평한지를 정량적으로 평가할 수 있다. </br><br/>

---

### Amenities

점수산정방식 : 

<img width="728" alt="amentities_01" src="https://github.com/Kyeong6/ParkScore/assets/100195725/73aead2d-e5f3-44ed-b24b-84a913ee689b">


전처리 과정 : [amenities_data_preprocessing](https://github.com/Kyeong6/ParkScore/blob/main/data_preprocessing/amenities/parkscore_amentities.ipynb)

공원의 시설은 시민들의 공원 이용 경험에 직접적인 영향을 미친다.

- 공원 시설의 밀도 평가 : 공원 내 시설물의 밀도를 평가하여 공원의 질을 판단한다.
- 시설물 접근성 : 다양한 시설이 잘 갖추어진 공원은 시민들의 접근성과 이용 편의성을 높인다.
- 자원 배분의 효율성 : 공원 면적당 시설물의 밀도를 평가함으로써 자원이 효율적으로 배분되었는지를 판단한다.
- 공원 이용의 균형성 : 공원 시설의 균형 잡힌 배치는 공원의 전반적인 이용 균형성을 높이는 데 기여한다.
- 질적 향상 : 공원 면적당 시설물의 밀도를 평가하는 지표로, 공원의 질을 향상시키고 공원 이용자의 만족도를 높이는 데 기여한다.
