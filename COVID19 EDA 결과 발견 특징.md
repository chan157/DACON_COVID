안녕하세요 [Mulcamer] 팀입니다.

저희 팀은 삼성 멀티캠퍼스에서 BigData/AI 설계 과정을 수강하는 학생들입니다.
부족한 부분 지적이나 추가하면 아이디어 등 소통은 언제나 환영입니다.

첫 번째 단계로 plotly와 tableu를 활용한 EDA와 시각화를 진행했습니다.
분석 내석 내용을 바탕으로 데이터의 특징과 코로나에 대한 분석 방향을 모색했습니다.

다음 포스팅에서는 분석 내용을 추가하여 포스팅하겠습니다.

 + 유익하고 재밌으셨다면 투표한번씩 부탁드립니다. ^__^  
 + 모든 데이터로 이루워진 EDA 다 보니 글이 다소 깁니다. 이 점 참고하시고 재미있게 봐주세요~



(4월 22일) COVID-19 Plotly를 사용한 전반적 EDA
(4월 23일) 시간에 따른 세계 확진자 추이 TABLEU
(4월 24일) 시간에 따른 한국 확진자 추이 TABLEU
(4월 26일) EDA 결과 및 특징을 통한 분석 방향 확립

태블로 주소 : https://public.tableau.com/profile/.12875783#!/vizhome/CoronavirusStatistics_15877072836610/1_1



제출용 태블로 주소 : https://public.tableau.com/views/CoronavirusStatistics_15877072836610/1_1?:retry=yes&:showVizHome=no&:embed=true





# COVID-19 EDA 결과 발견 특징

안녕하세요. No 1. Mulcampler 팀 입니다.  

저희는 본 경진대회의 데이터를 활용하여 전반적인 EDA를 통해 특징과 시사점을 생각해보았습니다.

## 결론 및 요약

###   1. 끝날때까지 끝난게 아니다! 

####   - 코로나는 감염성이 매우 높은 전염 질병이므로 대규모 집회와 모임, 외출 등을 삼가해야 합니다. 

###   2. 우리들의 궁금증은 이제 시작이다!

####   - 데이터를 탐색하며 주목한 5가지 특징은 다음과 같습니다.

#### 1. 20대 감염자는 어디서 왔는가?

1. 오히려 유동인구는 20대가 40, 50대 보다 낮은 것을 확인할 수 있습니다. 막연히 외부 접촉이 많았다고 결론짓기에는 부족한 부분이 있습니다.
2. 30, 40, 50대의 경우 직장 생활의 경우가 높고, 대학생의 경우 그 외의 활동들 예상할 수 있습니다.

#### 2. 압도적인 고연령자들의 사망률?

1. 경상도와 대구의 사망률이 높은 것을 확인할 수 있습니다. 특히나 경상도의 경우는 평균 연령이 시/도 중에서 두번째로 높은 곳입니다. 
2. 독거노인 비율 또한 함께 비교해볼 필요가 있을 것 같습니다.

#### 3. 서울경기와 대구와 경상도의 그래프 모양의 차이

1. 서울, 경기, 인천 :  꾸준히 증가추세인 감염자 모형

2. 대구, 경상도 :  신천지 집단 감염으로 급격한 증가 이후 급격한 감소

   > 두 지역간의 확연한 구분 차이를 비교해볼 필요가 있을 것 같습니다.

#### 4. PatientInfo 데이터의 대구지역 데이터 부족

1. 지역별에 따른 환자 State(released/isolated/deceased) 정보에 대해 분석을 진행하였습니다.

   하지만 대구지역의 환자 정보가 많이 부족함을 알 수 있었습니다.

   감염 경로 및 이동 경로 등을 파악해서 환자를 줄이기위해 1:1로 역학조사를 진행합니다. 하지만, 대구 지역 신천지 사태로 인해서 급격하게 증가한 대구 환자들을 모두 조사하기에 인력이 부족했고, 이로 인해서 자세한 정보가 부족한 것으로 예상할 수 있습니다.

2. 신규 확진자 수 증가 그래프를 보아도 신천지 이후 매우 심각하고 급박한 상황이었음을 예상할 수 있습니다.

 

















##########33

우리나라랑 다른나라의 증가 그래프 모양이 조금 다른듯??

신천지로 급격한 재급증 >> 다른나라들도 아주 조심해야한다.



????????????????????//

도입부에 우리나라외국의 칭찬들 넣고 우리나라의 조치 대응

