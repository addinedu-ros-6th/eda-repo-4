# :shipit: **대한민국 범죄 발생 현황 및 동향 분석**
> ***EDA Project Team 4 Repository: Analysis of Crime Incidence and Trends in South Korea***

## ➰ 개요

### 🗓️ 프로젝트 기간
- 7월 1일 - 7월 7일

### 💡 선정 배경 및 프로젝트 개요 
- 최근 사회적으로 안전에 대한 관심이 크게 높아지고 있어 범죄 발생 현황을 체계적으로 살펴보는 일이 중요해지고 있다.
- 단순히 범죄 발생 건수만 제시하는 것을 넘어 지역별·유형별 범죄 양상과 그 변화 추이를 분석함으로써 향후 정책 수립과 효과적인 예방 전략 수립에 도움이 되고자 한다.
- 본 프로젝트는 대한민국 범죄 발생 데이터를 바탕으로 시기별, 지역별 추세를 면밀히 검토하고 이를 통해 의미 있는 인사이트를 발굴하여 사회적 안전망 강화에 기여하고자 한다.

### 🙌 팀원 소개
|이름|담당|
|-----|-----|
|전재진 <br> (팀장)|데이터 SQL<br> .<br>.| 
|이재훈|. <br> . <br> . <br> .|
|김제백| 범죄 <br> . | 
|이시원|. <br> . <br> .|

### 🛠️ 기술 스택 
|분류|기술|
|-----|-----|
|개발 환경|![js](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white) |
|개발 언어| ![js](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)|
|DBMS|![js](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)|
|협업| ![js](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) ![js](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)|


<br>


## ➰ 데이터 분석
- before  [ 1994 ~ 2010 ]
- after  [ 2011 ~ 2022 ]

### 1️⃣ 총 범죄 & 범죄 유형별 발생 추세 분석
#### 🔗총 범죄 발생 특이점 분석
![image](https://github.com/user-attachments/assets/bfc1f0b9-706f-4c63-b444-a184a61e7b04)

<br>

#### 🔗범죄 유형별 발생 추세 분석

🔻before
| 강력범 & 절도범 |
| --- |
|<img src="https://github.com/user-attachments/assets/d7cf6b1b-2aef-4d71-ba5e-89a6cbc99fa0" height="300" width="800"/>|

| 폭력범 & 지능범 |
| --- |
|<img src="https://github.com/user-attachments/assets/39b1378f-1b12-4b1f-a885-ac4e7ed43e34" height="300" width="800"/>|

| 풍속범 |
| --- |
|<img src="https://github.com/user-attachments/assets/db3fefad-a53d-4fb8-8778-1ecb71adbd95" height="300" width="350"/>|

<br>

🔻after
| 강력범 & 절도범 |
| --- |
|<img src="https://github.com/user-attachments/assets/6de0b0a5-3630-448c-a933-24a5cb389db7" height="300" width="800"/>|

| 폭력범 & 지능범 |
| --- |
|<img src="https://github.com/user-attachments/assets/dce55fa1-31d7-4a46-90d4-172a1c5819de" height="300" width="800"/>|

| 풍속범 & 교통범 |
| --- |
|<img src="https://github.com/user-attachments/assets/827408ec-fc63-4f32-9706-4a91bcec6178" height="300" width="800"/>|

<br>

📍 **[ 분석 결과 요약 ]**
> <img src="https://github.com/user-attachments/assets/e0432115-b746-4759-b016-45c1138b5e87" height="300" width="750"/>

### 2️⃣ 범죄 유형별 세부 분석
#### 🔗강력범
<details close>
<summary>before</summary>
<table>
  <tr>
    <th>연도별 강력범죄 종류에 따른 발생 건수</th>
    <th>지역별 발생한 강력범죄 발생 건수</th>
    <th>장소별 발생한 강력범죄 발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/c026f788-aeea-4f3f-a6b5-27fc97724aa6" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/558d61bb-a76d-40d0-bd97-9bae4b258081" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/219ed4f1-16fd-44f9-be4a-de869662f45b" height="150" width="400"/></td>
  </tr>
</table>
  <table>
  <tr>
    <th>요일별 강력범죄 종류에 따른 <br/>발생 건수</th>
    <th>시간별 발생한 강력범죄 <br/>발생 건수</th>
    <th>범행 연령별 발생한 강력범죄 <br/>발생 건수</th>
    <th>범행 동기별 발생한 강력범죄 <br/>발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/44cbf45f-7452-4212-8607-a9391ef43df3" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/672e3da0-b5bd-4fd6-be81-a9a6c3acaf06" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/5c3fc96e-26d4-49c9-9b1a-e908b7a4c03d" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/d826445c-0734-45c0-bf96-256337db813b" height="150" width="300"/></td>
  </tr>
</table>

<br>

📍 **[ 분석 결과 요약 ]**
> ![강력범죄 분석 결과](https://github.com/user-attachments/assets/28d3979c-a320-4725-8afd-53c10212fd41)

</details>

<details close>
<summary>after</summary>
<table>
  <tr>
    <th>연도별 강력범죄 종류에 따른 발생 건수</th>
    <th>지역별 발생한 강력범죄 발생 건수</th>
    <th>장소별 발생한 강력범죄 발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/84f4399d-6384-4b4c-995e-130b09523b7a" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/2fbb8ef5-99aa-4114-863a-8c895932c61b" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/cbb4ce60-6310-41b6-831d-fdab25a34cde" height="150" width="400"/></td>
  </tr>
</table>
  <table>
  <tr>
    <th>요일별 강력범죄 종류에 따른 <br/>발생 건수</th>
    <th>시간별 발생한 강력범죄 <br/>발생 건수</th>
    <th>범행 연령별 발생한 강력범죄 <br/>발생 건수</th>
    <th>범행 동기별 발생한 강력범죄 <br/>발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/a053b35a-38a9-4483-9728-7915e0e4d0c1" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/0aaa89ca-41cf-4fd7-a9b0-fdf1643fc120" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/350eec35-2111-49a7-9201-89b1d03d43e0" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/c5fbef24-b15e-4688-90c4-1bf53968e5b7" height="150" width="300"/></td>
  </tr>
</table>

<br>

📍 **[ 분석 결과 요약 ]**
> ![강력범죄 분석 결과](https://github.com/user-attachments/assets/0994ccf4-efd5-4518-b4dc-fbfa2d18a8e6)

📍 **[ after 특이점 연도의 원인 분석 ]**
>  💥 **강력범 유형별 중 성관련 범죄(강간, 강제추행) 급증**<br>
>  &nbsp;&nbsp;&nbsp;⇒ 전체적인 강력 범죄 증가
>
>  💥 **사회 인식의 변화로 인해 성범죄 증가**
>
>  💥 **근거 뉴스**<br>
>  &nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/98f008d1-13b1-4ae6-b47b-3e3d0858fd71" height="200" width="300"/><br>
>  &nbsp;&nbsp;&nbsp;⇒ [10년간 성범죄 급증…‘사회인식 변화’ 반영](https://www.mk.co.kr/news/all/2038564)

</details>

#### 🔗절도범
<details close>
<summary>before</summary>
<table>
  <tr>
    <th>연도별 절도범죄 종류에 따른 발생 건수</th>
    <th>지역별 발생한 절도범죄 발생 건수</th>
    <th>장소별 발생한 절도범죄 발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/0b19da0a-bdf2-4dfd-8b40-31e153092d23" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/70cf8d19-05e2-4dbb-85cd-7394e299117e" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/45a07e40-d5bd-447a-80f5-485726cdb371" height="150" width="400"/></td>
  </tr>
</table>
  <table>
  <tr>
    <th>요일별 절도범죄 종류에 따른 <br/>발생 건수</th>
    <th>시간별 발생한 절도범죄 <br/>발생 건수</th>
    <th>범행 연령별 발생한 절도범죄 <br/>발생 건수</th>
    <th>범행 동기별 발생한 절도범죄 <br/>발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/f989089b-9e62-49ac-b487-e1db4347139e" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/d93d5150-d470-4432-88ea-43b3453689fa" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/ffaa31a4-9fe5-4a55-aa04-a8e066d7ee83" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/33d52a7a-dd3f-4077-b64e-94bdf9a1f447" height="150" width="300"/></td>
  </tr>
</table>

<br>

📍 **[ 분석 결과 요약 ]**
> ![절도범죄 분석 결과](https://github.com/user-attachments/assets/07ed0410-8260-43d1-864f-f651c7a7ab0e)

📍 **[ before 특이점 연도의 원인 분석 ]**
>  💥 **IMF로 인한 경제 수준 급감(실업률 등)**<br>
>  &nbsp;&nbsp;&nbsp;⇒ 생계형 절도 범죄 급증
>
>  💥 **근거 뉴스**<br>
>  &nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/332082cf-2e3f-4408-a519-1dfb52fc6d30" height="200" width="300"/><br>
>  &nbsp;&nbsp;&nbsp;⇒ [IMF형 장기화로 생계형 범죄 극성](https://www.mk.co.kr/news/all/2038564)
>
> 💥 **근거 데이터**<br>
> &nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/e4226e2a-c7da-4ee6-b079-349bd0b701ae" height="200" width="300"/>

</details>

<details close>
<summary>after</summary>
<table>
  <tr>
    <th>연도별 절도범죄 종류에 따른 발생 건수</th>
    <th>지역별 발생한 절도범죄 발생 건수</th>
    <th>장소별 발생한 절도범죄 발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/45824b1e-fc02-460a-9788-e78e4002b292" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/4b9ed304-b467-4820-8f8d-71223fa2b62b" height="150" width="400"/></td>
    <td><img src="https://github.com/user-attachments/assets/455fffa1-5371-4897-8ce1-669edbd6777a" height="150" width="400"/></td>
  </tr>
</table>
  <table>
  <tr>
    <th>요일별 절도범죄 종류에 따른 <br/>발생 건수</th>
    <th>시간별 발생한 절도범죄 <br/>발생 건수</th>
    <th>범행 연령별 발생한 절도범죄 <br/>발생 건수</th>
    <th>범행 동기별 발생한 절도범죄 <br/>발생 건수</th>
  </tr>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/49ceef83-5368-4270-84a2-3480e3703c66" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/0ec4dce2-6300-4c05-9bf6-c8a6b341d2a5" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/ffe82d6e-7927-489b-aa2e-4e2811f97bb1" height="150" width="300"/></td>
    <td><img src="https://github.com/user-attachments/assets/41b7517d-d47e-4614-ba70-448485f254a5" height="150" width="300"/></td>
  </tr>
</table>

<br>

📍 **[ 분석 결과 요약 ]**
> ![절도범죄 분석 결과](https://github.com/user-attachments/assets/0fb77f56-b4bc-41ca-8d77-f0e6d82dfe49)

📍 **[ after 특이점 연도의 원인 분석 ]**
>  💥 **절도 범죄 발생 수가 꾸준히 증가하다가 2015년부터 줄어든다**<br>
>  &nbsp;&nbsp;&nbsp;⇒ CCTV, 블랙박스 범죄 예방용 카메라 작용
>
>  💥 **범죄 트랜드 변화 발생(피싱)**
> 
>  💥 **근거 뉴스**<br>
>  &nbsp;&nbsp;&nbsp;<img src="https://github.com/user-attachments/assets/096a6633-f89a-49d9-b924-e3e1dfff30f1" height="200" width="300"/><br>
>  &nbsp;&nbsp;&nbsp;⇒ [서울 '공공감시CCTV' 14만여대... 2년새 두 배 급증 '세계 최상위권'](https://www.hani.co.kr/arti/economy/it/1093078.html)

</details>



## 결론


## 고찰

