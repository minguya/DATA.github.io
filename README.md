# 백신접종률에 따른 Covid-19 확진자 추이 분석 및 예측
1.   백신접종률이 활발하게 이루어지고 있는 국가 **칠레, 이스라엘, 영국, 미국**을 대상으로 데이터 분석
2.  백신접종률/백신종류가 Covid-19 확산 및 사망률에 어떠한 영향을 미치는지 분석 후 인사이트 도출

## 프로젝트 소개


* **프로젝트 기간 : 2021-05-10 ~ 2021-06-10**
* **참여자 : 김수민 이솔비 최순현**
* **기획의도**
> COVID-19 백신접종이 전세계적으로 활발하게 이루어지고 있다.
대한민국을 포함한 백신접종이 활발한 4개 국가를 선정하여 백신 접종 전과 후의 데이터 분석을 통해 백신접종이 COVID-19 확진자 및 사망자 추이에 어떠한 영향을 미치는지 분석하고 미래의 COVID-19 확진자 예측 분석을 통해 COVID-19 종식에 대한 인사이트 및 솔루션을 제안한다.
* **자세한 데이터 분석은 위의 파일에서 확인하실 수 있습니다**
* **파일이 열리지 않을  Reload**


## 1-1. 백신접종률이 높은 4개 국가 (칠레, 이스라엘, 영국, 미국) COVID-19 데이터 분석
> COVID-19 백신접종률이 높은 4개 국가 칠레/이스라엘/영국/미국의 COVID-19 신규확진자, 신규사망자, 백신접종률에 대한 데이터 분석을 진행한다. 
* **신규 확진자**
<img width="629" alt="신규확진자" src="https://user-images.githubusercontent.com/86412748/125388543-a248fc80-e3da-11eb-9c59-63ddb182f561.png">
<img width="1038" alt="신규확진자2" src="https://user-images.githubusercontent.com/86412748/125388808-2602e900-e3db-11eb-8f62-8509d567ed39.png">


* **신규 사망자**
<img width="623" alt="신규사망자" src="https://user-images.githubusercontent.com/86412748/125388569-ad039180-e3da-11eb-816c-52ebd0821822.png">

* **백신 타입 비교**
> 이스라엘/영국/미국의 COVID-19 신규확진자는 감소하고 있는 반면 칠레의 COVID-19 신규확진자는 백신접종을 진행중임에도 불구하고 상승하고 있는 양상을 띄고 있다. 
> 칠레와 미국의 백신 타입 비교 결과 미국은 모더나/화이자 백신 비율이 높은 반면, 칠레는 시노백 백신 비율이 높은 것을 확인할 수 있다.
> 이에 시노백 백신보다는 모더나/화이자 백신의 효과가 더 좋을 수 있다는 예측을 해볼 수 있다. 

<img width="777" alt="칠레 백신" src="https://user-images.githubusercontent.com/86412748/125388995-79753700-e3db-11eb-9137-87ad4b5cf13c.png">
<img width="777" alt="미국 백신" src="https://user-images.githubusercontent.com/86412748/125389012-7e39eb00-e3db-11eb-8900-7b614a3e4ec5.png">


## 1-2. 백신접종률이 높은 4개 국가 (칠레, 이스라엘, 영국, 미국) COVID-19 신규 확진자 예측 분석
### Facebook Prophet을 활용한 주가 예측 모델

* **칠레**
<img width="713" alt="칠레 확진자 예측" src="https://user-images.githubusercontent.com/86412748/125389437-29e33b00-e3dc-11eb-9974-47cbac1a61c6.png">

* **이스라엘**
<img width="714" alt="이스라엘 확진자 예측" src="https://user-images.githubusercontent.com/86412748/125389446-2fd91c00-e3dc-11eb-85ca-4f6b1941ef14.png">

* **영국**
<img width="714" alt="영국 확진자 예측" src="https://user-images.githubusercontent.com/86412748/125389454-323b7600-e3dc-11eb-91a1-48bbd7f9723e.png">

* **미국**
<img width="713" alt="미국 확진자 예측" src="https://user-images.githubusercontent.com/86412748/125389463-35cefd00-e3dc-11eb-9b37-dc434468ab5e.png">


## 2-1. 대한민국 COVID-19 데이터 분석
> 대한민국의 COVID-19 신규확진자, 신규사망자, 백신접종률에 대한 데이터 분석을 진행한다. 

* **신규 확진자**
<img width="618" alt="한국 신규확진자" src="https://user-images.githubusercontent.com/86412748/125390206-6ebba180-e3dd-11eb-8e27-b3d6d78fc1bf.png">

* **신규 사망자**
<img width="606" alt="한국 신규사망자" src="https://user-images.githubusercontent.com/86412748/125390216-72e7bf00-e3dd-11eb-84f3-82b34e0c914c.png">

## 2-2. 대한민국 COVID-19 신규 확진자 예측 분석
### Facebook Prophet을 활용한 주가 예측 모델

* **대한민국**
<img width="713" alt="한국 확진자 예측" src="https://user-images.githubusercontent.com/86412748/125390325-a9bdd500-e3dd-11eb-9a65-5fc4b5af7222.png">


## 2-3. 대한민국 COVID-19 백신 예방접종에 대한 인사이트

1. COVID-19 백신 접종에 따라 COVID-19 확진자/사망자의 수가 감소하고 있는 추세이다. 
지속적인 거리두기 및 방역 정책을 지속함에 따라 COVID-19 바이러스 전파가 낮아질 것으로 예상하지만, 무증상 전파와 더불어 새롭게 나타나고 있는 변이 바이러스의 영향력 등 다양한 요인으로 인해 7월 말부터 확진자가 서서히 증가할 것으로 예측된다. 

2. COVID-19 바이러스의 전파력을 낮추고, 중증 및 사망 환자 발생율을 최소화 시키기 위하여 COVID-19 백신 접종은 필수사항으로 예상한다. 
