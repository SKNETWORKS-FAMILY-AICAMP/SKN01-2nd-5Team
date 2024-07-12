# SKN01-2nd-5Team
<div align="center">
<img width="600" alt="image" src="https://github.com/Jh-jaehyuk/Jh-jaehyuk.github.io/assets/126551524/7ea63fc3-95f0-44d5-a0f0-cf431cae34f1">

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

## Vue + Django + FastAPI 기반 가입 고객 이탈 예측 및 구매 동향 예측 

플레이데이터 SK Networks AI Camp 2차 프로젝트

</div>

## WBS를 Agile Board(애자일 보드) 로 변경

```c
실제로 우리는 수업 초반부터 프로세스를 학습하여
과정 전반에 걸쳐 애자일 프로세스를 사용하며 Backlog를 작성하고 있습니다.
그러므로 폭포수 방식의 WBS 보다는 저희가 사용하는 애자일 프로세스에 맞게
애자일 보드의 Status View와 Domain View를 위주로 업로드하기로 하였습니다.
```

# 1. 팀 소개
### BBZ(The Backlog BusterZ)
| 한재혁 | 이민재 | 이경민 | 최명근 | 박주현 |
|:----------:|:----------:|:----------:|:----------:|:----------:|
| <img width="120px" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/41e20818-5f78-4a66-a11e-cc81e1abe511" /> | <img width="120px" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/9d1b48c8-50f0-4cfc-90d4-57be71b3c884" /> | <img width="120px" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/7c28355a-889b-4e3a-8423-c799d1e44825" /> | <img width="120px" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/e6f3eba6-082b-491a-8f29-9fef49d50cd1" /> | <img width="120px" src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/7b02b779-99eb-4f38-9391-93f8275fbbeb" /> 
|  [@Jh-jaehyuk](https://github.com/Jh-jaehyuk) | [@Meue-L](https://github.com/Meue-L) | [@2kilometer](https://github.com/2kilometer) | [@RUVIST](https://github.com/RUVIST) |[@iksoo-park](https://github.com/iksoo-park/skn-1st) |


# 2. 프로젝트 개요

### 프로젝트 명
*Walkerhill*

### 프로젝트 소개
*Walkerhill* 호텔을 이용하는 **고객의 동향을 분석하여 호텔을 추천**해주고 **고객이 얼마나 이탈할 것인지 예측**할 수 있습니다.

### 프로젝트 필요성(배경)
*Walkerhill*은 서울에 3개의 호텔과 공항에 2개의 호텔을 가지고 있습니다.  
많은 선택지는 고객으로 하여금 선택의 폭을 늘려준다는 장점이 있지만,  
호텔이 서로 뚜렷하게 구분되지 않는다면 **어떤 호텔을 선택하는 것이 좋을지 알기 어렵다는 단점** 또한 존재합니다.  
저희는 이러한 문제점을 해결하기 위해서 **고객들의 동향을 분석**하여 호텔을 예약하고자 하는 고객들에게 **어떤 호텔을
선택하는 것이 좋을지 추천**해주는 웹사이트를 개발하고자 하였습니다.
또한, 운영적인 측면에서 **어떤 고객들이 서비스를 계속 이용하지 않고 이탈할 가능성이 높은지 파악**할 수 있도록 하여
장기적인 서비스 운영에 도움을 주고자 하였습니다.

### 프로젝트 목표
1. 원활한 웹사이트 운영을 위해, Backend Service로 **Python**과 **Django**를 이용하였습니다.  
2. 더불어 Frontend에서는 사용자에게 보이는 웹디자인적인 측면에서 유리한 **TypeScript**와 **Vue.js + Vuetify3**를 이용하였습니다.  
3. 마지막으로 분석에서는, **Logistic Regression**을 이용하여 고객의 동향을 분석히였고 **AARRR 분석 방법**을 이용하여 관리자가 고객의 이탈율을 계산할 수 있도록 하였습니다.


# 3. 기술 스택 :books:

### Backend
<img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white"/> ![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white) <img src="https://img.shields.io/badge/pandas-%23150458?style=for-the-badge&logo=pandas&logoColor=white"/> <img src="https://img.shields.io/badge/numpy-%23013243?style=for-the-badge&logo=numpy&logoColor=white"/>

### Frontend
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/> <img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"/> <img src="https://img.shields.io/badge/vuetify-%231867C0?style=for-the-badge&logo=vuetify&logoColor=white"/> <img src="https://img.shields.io/badge/axios-%235A29E4?style=for-the-badge&logo=axios&logoColor=white"/>

### Collaboration
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white) <img src="https://img.shields.io/badge/notion-%23000000?style=for-the-badge&logo=notion&logoColor=white"/> <img src="https://img.shields.io/badge/slack-%234A154B?style=for-the-badge&logo=slack&logoColor=white"/>

### IDE
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white) <img src="https://img.shields.io/badge/pycharm-%23000000?style=for-the-badge&logo=pycharm&logoColor=white"/>

### AI Core
<img src="https://img.shields.io/badge/fastapi-%23009688?style=for-the-badge&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/scikitlearn-%23F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>

### Infrastructure
<img src="https://img.shields.io/badge/docker-%232496ED?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/redis-%23FF4438?style=for-the-badge&logo=redis&logoColor=white"/> ![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Graphviz](https://img.shields.io/badge/Graphviz-used-blue.svg)

# 4. 가설 검정

### 가설
* **가설1**: 구매 이력이 없으면 **이탈율이 높을 것**이다.
* **가설2**: 재구매 이력이 있다면 **이탈율이 낮을 것**이다.
* **가설3**: 상품을 공유한 이력이 있다면 **이탈율이 낮을 것**이다.

### 가설 검정
* **데이터 수집 결과**
  <img src="https://github.com/user-attachments/assets/0c7054b5-417a-4a1f-bf62-41e68ff702fd"/>
  <img src="https://github.com/user-attachments/assets/3cf85c4c-9672-40d8-8568-d8f76c0518ad"/>

* **데이터 분석**
  <div align="center">
    <img src="https://github.com/user-attachments/assets/5ca0bb68-7555-4d54-a2a5-02138fb8d791"/>
  </div>
  
  * 상관관계 분석 결과, **상관관계로 분석하는 것이 무의미하다고 판단**하여 분석에서 제외함

* **모델 학습**
  <div align="center">
    <img src="https://github.com/user-attachments/assets/04fbe5dc-d576-4997-92f9-39de9fdb5457"/>
  </div>
  
  * *Logistic Regression* 모델 학습 결과, *roc curve*가 이상적으로 그려져 **회귀 모델로 분석이 가능할 것**으로 판단함
  
* **분석 결과**
  * *수집 → 활성 → 구매 → 재구매 → 공유* 로 넘어갈수록 **이탈율이 낮아짐**을 확인
  * 따라서, **가설이 성립함**을 확인할 수 있음


# 5. Agile Board (애자일 보드)

## Django
<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/d31cb745-57f9-4c7c-b0e6-02c5d29c60fc"/>

## Vue
![vue백로그](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/168423037/fb286210-e9cc-4351-9543-f4c8493973cd)

## FastAPI
![fastali백로그](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/168423037/42bc2eca-47e8-4873-bf63-d40ed91a9638)

# 6. Commit History (커밋 이력)

## Django
![image1](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/a56f0f62-d6ff-4a98-8bde-2f1b3d2d4fb6)

## Vue
![image2](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/a56f0f62-d6ff-4a98-8bde-2f1b3d2d4fb6)

## FastAPI
![image3](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/1cc8f021-5290-4a56-98c9-d5e488a1084e)

# 7. 발생한 이슈 내역  

## 우선 순위를 5 단계로 나눠서 관리  

```c
실제 서비스를 운영한다는 마인드로 현실 상황에서 발생하는 크고 작은 이슈들이 존재할 것입니다.
이 서비스들에서 회사 입장에서 매출에 중요한 것과 중요하지 않은 것들이 있을 것입니다.
이와 같은 사항들을 실질적으로 고려하여 이슈 관리를 진행합니다.
```
  
### 급하지않음
* 서비스가 가능하면서 사용자들은 불편함을 느끼지 못하여 매출에 지장이 전혀 없는 경우  
    ![issue1](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/464a12d6-26d4-4e2c-921f-f9ed95290370)
### 보통
* 서비스가 불가능하여 기능을 하지 못하지만 수정하기 어렵지 않은 경우
    ![issue2](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/606ce865-0868-4693-9ec4-1f8b04ca2fd8)
### 급함
* 개발 막바지, 서비스 배포 직전에 문제가 생겨서 기능을 하지 못하는 경우
   ![issue3](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/a134df1b-49f3-4e20-810a-8e1db446ee91)
### 매우 급함
* 개발 초반부터 문제가 생겨 이후 연관된 모든 개발 진행에 차질이 생기는 경우
    ![issue4](https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/126551524/27b56023-cc2c-4905-84b7-8b0e34e2710a)

# 8. ERD
<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/0c38f744-c977-4807-a6d2-92ff0b68b68c"/>

# 9. 주요 Domain 요소들

### board
* `Q&A 게시판` 관리를 위한 Domain
### product
* `호텔 정보` 관리를 위한 Domain
### account
* `회원` 관리를 위한 Domain
### kakaoOauth
* `Kakao 로그인`을 위한 Domain
### orders
* `주문 정보` 관리를 위한 Domain
### favorites
* `즐겨찾기 정보` 관리를 위한 Domain
### marketing
* `AARRR 분석을 위한 데이터`를 관리하기 위한 Domain

# 10. 수행결과(테스트/시연 페이지)

### 메인 화면
<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-1st-5Team/assets/168423037/eadc16be-2c03-401d-b4b9-27ffbb6cd5c9"/>

### 개인별 호텔 추천 서비스
<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/168423037/0215b44b-b0aa-48be-833d-4a7a5602fd52"/>

### AARRR 분석 페이지
<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/168423037/ff46ab8d-00bb-4c4a-b875-17162b703ff6"/>
<img src="https://github.com/SKNETWORKS-FAMILY-AICAMP/SKN01-2nd-5Team/assets/168423037/caa0dc76-b158-4293-b0b7-a70ab87bfb13"/>


# 11. 한 줄 회고

- 🧔**한재혁**: 짧은 기간동안 많은 기능들을 구현하려고 하다보니 쉽진 않았지만 그래도 힘든만큼 성장하는 것이라고 생각해서 성공적으로 마무리한 것 같습니다.

- 👩‍🦱**이민재**: 개인적인 이슈가 있어 뒤늦게 합류해 부족한 점도 많았을 텐데, 다들 옆에서 잘 알려주시고 이끌어주셔서 잘 마무리 할 수 있었던것 같습니다. 다들 고생 많으셨습니다.

- 👩‍🦰**이경민**: 사용자 이탈률 예측 서비스를 end-to-end로 구축을 하며 어떻게 데이터가 쌓이고 가공되고 활용되는 지 직접 경험해볼 수 있어서 데이터에 대한 이해도가 높아진 프로젝트였습니다.

- 👨‍🦳**최명근**: 머신러닝 결과를 사용자한테 전달하는 서비스를 제대로 해본 경험이었습니다. 예전부터 기계학습 결과를 어떻게 제공할지 고민이 많았는데 백엔드를 경험할 수 있어서 좋았습니다.

- 👨‍🦲**박주현**: 지난 프로젝트 덕분에 많이 성장했고, 앞으로 어떻게 공부해야 할지 방향성이 보였습니다!

