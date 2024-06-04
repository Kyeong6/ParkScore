# ParkScore Ranking: 대한민국 85개 도시

팀명 : GPS(Green Park Score)

설명 : 도시공원의 현재와 미래를 평가하는 ParkScore: 시민과 지자체를 위한 플랫폼
</br><br/>

## 개발 배경 및 목적

**개발 배경**

현대 도시 환경에서 공원의 중요성은 날로 증가하고 있다. 도시의 인구 밀집과 환경 문제는 시민들에게 쾌적한 생활환경을 제공하는 공원의 필요성을 더욱 부각시키고 있다. 이러한 배경에서 전국 도시공원의 정보를 종합적으로 제공하고, 이를 통해 지자체가 효율적으로 도시공원 계획을 수립할 수 있도록 돕기 위한 한국형 ParkScore의 개발이 필요하다고 판단하였다.

<img width="960" alt="background_01" src="https://github.com/Kyeong6/ParkScore/assets/100195725/2a782263-6ef8-499e-9a80-a8b84f92cc5c">


</br><br/>
<img width="960" alt="background_02" src="https://github.com/Kyeong6/ParkScore/assets/100195725/1f50f4cf-e182-40e8-b80f-ec64ba7338f4">
</br><br/>

한국형 ParkScore는 공공데이터 포털, 국토지리정보원, KOSIS 등 신뢰할 수 있는 기관의 데이터를 활용하여 전국 도시공원의 접근성, 면적, 투자, 공평성, 시설이라는 5개의 주요 지표를 설정하고, 이를 바탕으로 점수와 순위를 산정하여 제공한다.
</br><br/>

**목적**

본 서비스를 통해 도시민과 지자체에게 긍정적인 영향을 줄 수 있다.

> 도시민
> 

| 목적 | 설명 |
| --- | --- |
| 공원 접근성 개선 | 지표를 통해 어려운 접근성을 가진 지역을 파악하고, 공원 건설 및 개선을 우선적으로 추진하여 시민들에게 더 나은 도시공원 환경 제공 |
| 시민 참여 활성화 | 지표를 공개적으로 제공함으로써 시민들이 도시공원 개선에 대한 의견을 제시하고, 지역 사회와 함께 녹지 공간을 관리하고 발전시키는 데 기여 |

</br><br/>
> 지자체
> 

| 목적 | 설명 |
| --- | --- |
| 도시 계획의 기준 제공 | 지속 가능하고 건강한 도시 환경을 조성하는 데 필요한 정보와 지침을 제공하여 방향성 설정에 기여 |
| 도시 이미지 및 브랜드 형성 | 지표를 통한 도시 별 순위 공개는 경쟁력을 높이는 긍정적인 영향을 주어 도시 홍보 및 마케팅에 활용 |

</br><br/>
## 공공데이터의 활용과 지표정보

**공공데이터 활용**

ParkScore Ranking 서비스는 신뢰성 높은 공공데이터를 활용하여 전국 도시공원의 접근성, 면적, 투자, 공평성 시설 등 5개의 주요 지표를 설정하고 이를 바탕으로 점수를 매기고 순위를 결정 하였다. 이를 통해 도시공원의 현황을 종합적으로 평가하고, 지자체와 시민들에게 유용한 정보를 제공한다.
</br><br/>

**지표정보**

점수산정방식  :  [Scoring method](https://github.com/Kyeong6/ParkScore/tree/main/result)

</br><br/>

> 접근
> 

| 데이터 | 생활권공원 서비스 권역 내 인구수(0.75km) |
| --- | --- |
| 보유기관 | 국토정보플랫폼 국토통계지도 |
| 분야 | 인구 통계 |
| 중요성 | 공원의 접근성은 시민들의 이용 편의성을 직접적으로 반영 |

</br><br/>

> 면적
> 

| 데이터 | 전국도시공원표준데이터 |
| --- | --- |
| 보유기관 | 공공데이터 포털 |
| 분야 | 도시면적 및 도시공원 면적 |
| 중요성 | 도시공원의 면적은 시민들이 이용할 수 있는 공간의 크기를 의미 |

</br><br/>

> 투자
> 

| 데이터 | 지자체의 도시공원 관련 부서 예산안 |
| --- | --- |
| 보유기관 | 각 지자체 홈페이지 |
| 분야 | 재정 |
| 중요성 | 공원에 대한 투자는 공원의 유지 및 발전 가능성 표시 |

</br><br/>

> 공평
> 

| 데이터 | 지역통계(지자체 기본통계) 토지 및 기후 행정구역 데이터 |
| --- | --- |
| 보유기관 | KOSIS, 각 지자체 홈페이지 |
| 분야 | 행정 구역 및 토지 통계 |
| 중요성 | 공원의 분포가 공평하게 이루어졌는지 평가 |

</br><br/>

> 시설
> 

| 데이터 | 전국도시공원표준데이터, 도시공원 시설데이터 |
| --- | --- |
| 보유기관 | 공공데이터 포털, 정보공개포털(청구) |
| 분야 | 도시공원 별 시설물 통계 |
| 중요성 | 공원의 시설은 공원의 기능성과 편의성을 결정하는 중요한 요소 |

</br><br/>

## 서비스의 구성

<img width="1524" alt="website" src="https://github.com/Kyeong6/ParkScore/assets/100195725/3c8b4fb2-60d1-49d3-997d-83eeba10cf04">

서비스 확인 : [GPS's ParkScore](https://korea-parkscore.pages.dev/)
</br><br/>

> ParkScore Weight
> 

5개의 지표가 각각 20%씩의 가중치가 부여된다. 화살표를 이동시켜 가중치를 변경하면 각 지표의 점수에 따라 순위가 변동된다.
</br><br/>

> 도시 검색
> 

도시의 각 지표 별 세부 점수를 시각적으로 표현되어 있고, 검색 기능을 통해 자신이 거주하는 도시나 관심 있는 도시의 점수를 쉽게 파악할 수 있다.
</br><br/>


## 서비스의 사회적 파급효과(ESG 혁신)

도시공원 평가 시스템은 단순히 공원의 상태를 평가하고 순위를 매기는 것에 그치지 않고, 통합된 데이터 구축을 통해 공공자원의 효율적 사용을 촉진하고 시민 참여를 유도한다.

공원 점수와 순위가 공개되면 각 지자체는 공원 관리 현황과 성과를 명확히 파악할 수 있게 된다. 이로 인해 지자체는 공원 관리 및 투자의 질적 향상을 도모하게 되며, 이는 보다 높은 평가를 얻기 위한 동기를 부여한다.

공원의 상태와 관리 수준에 대한 명확한 지표는 지자체가 효과적인 자원 배분과 투자를 통해 공공 자원의 투명하고 책임있는 사용을 촉진하게 한다. 또한, 이러한 시스템은 지자체 간의 건전한 경쟁을 유도하여 전반적인 공원 관리 수준을 향상시키고 주민들에게 보다 나은 도시공원 환경을 제공하는 데 기여할 수 있다.

특히, 공원의 확장은 탄소중립 목표 달성에 중요한 역할을 할 수 있다. 공원은 식물의 광합성을 통해 이산화탄소를 흡수하고 산소를 배출하는 기능을 한다. 따라서 공원의 면적이 확대되면 도시의 탄소 흡수 능력이 증가하게 된다. 이는 도시의 탄소 발자국을 줄이는 데 기여하며, 장기적으로 기후 변화 대응 능력을 강화한다. 또한, 공원이 도심 지역에 고르게 분포하면 도시 열섬 현상이 완화되고, 여름철 온도를 낮추어 에너지 소비를 줄이는 효과를 가져올 수 있다. 

이러한 효과는 ESG(Environmental Social Governance)경영의 환경 분야에서 좋은 영향을 끼칠 수 있다. 공원의 균형 있는 분포와 확장을 통해 도시의 지속 가능한 발전을 지원하며, 탄소중립 목표 달성에 기여함으로써 ESG경영의 모범 사례로 자리매김 할 수 있다.
