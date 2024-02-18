# 2023 구미산단 에너지자급자족 데이터톤
 
![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/73e027be-996b-4158-a8f6-0156e6bbca57)

<br/><br/>

# 🏆 Prize
![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/675b8911-d60c-4c34-885f-772a588fed9c)

<br/><br/>

# ✨ Team K2R1
1. 구성원
* 팀장: 전민욱 - 국립금오공과대학교 산업경영공학전공 3학년
* 팀원: 최재준 - 국립금오공과대학교 산업경영공학전공 3학년 
* 팀원: Salakhov Tagir - 국립금오공과대학교 산업경영공학전공 3학년

<br/>

2. 주 임무
* 전민욱 - 데이터 분석, 서비스 기획, AI 설계
* 최재준 - 서비스 기획, 데이터 분석
* Salakhov Tagir - AI 설계, 데이터 분석

<br/><br/>

# 🗂 Presentation
## 1. Data
1. 구미 에너지자급자족사업 참여기업 A사 2023.07.26 시간별 에너지 사용량 데이터
2. 한국전력공사 데이터 - 2020~2022년 데이터톤 DB(전력사용량, 태양광 발전) + 전력사용량은 1시간 간격, 태양광 발전은 15분 간격
3. 수요 및 설문조사 데이터 - 2023년 구미산업단지공단 스마트에너지클러스터 기업 설문조사 및 수요조사 

<br/><br/>
## 2. Problem Definition & Service Design
- '스마트에너지클러스터 기업 설문조사 및 수요조사'에 대한 분석
![그림2](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/263efd29-44fa-4133-be35-2c3102746fa1)

<br/><br/>
## 3. Modeling
- AI 모델 구현 로드맵
![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/b790f4db-db7f-46ac-b2f4-7a73f2e42b43)


- 사용 알고리즘

1.) Linear Models (선형모델) – Linear Regression, SVR

2.) Neural Networks (인공신경망) – Neural Network (tensorflow), MLPRegression

3.) Ensemble Models (앙상블) – Random Forest, Ensemble Models using Voting/Stacking 등

4.) Gradient Boosting (그래디언트 부스팅) – LGBM Regression, Gradient Boosting Regression

5.) RNN – LSTM

6.) KNN



<br/><br/>
## 4. Data Analysis And Results 
- Clustering & AI Model 학습 결과

  **최적 예측 모델** = `Ensemble Model` 


     (1) 구미산단 데이터톤 전력사용량 데이터
     ![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/4c01505b-8f5a-4e1f-882f-9826820a92cd)



     (2) 구미산단 데이터톤 태양광 발전량 데이터
     ![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/3271426a-e849-440e-bb21-a1c0e6078cbb)



     (3) 구미 에너지자급자족사업 참여기업 A사 전력량 데이터
     ![image](https://github.com/jaejunchoe/2023-Gumi-Industrial-Complex-Energy-Self-Sufficiency-Datathon/assets/157339263/81966e72-1443-41c7-b2b9-28e19919435f)

<br/><br/>
## 5. 결론 및 한계




