# DATATHON_TEAM1

## 수정사항.
### 4월 16일 오류
- 스탯티즈 크롤링 selenium 사용으로 IP 차단 (Colab 사용)
- 해결책 : Local에서 코드 구현 (성공)
- 결론 : 코랩에서는 스탯티즈 크롤링이 지원이 안되는 것을 확인

### 4월 17일 오류 (14:40)
- 로컬에서 너무 많은 요청을 한 탓인지, IP Block이 되는 것을 확인

### 4월 22일 오류 해결
- IP 변경 후에야 스탯티즈 사이트 접속 가능
- 스탯티즈 크롤링 지원 X, 너무 빠른 시간 내에 Drag & Drop하면 너무 많은 요청이 걸려 잠시 Ban이 될 수 있음

## 가설 9. FA선수가 되어 연봉이 오른 선수의 경우 차기 년도 성적이 좋을 것이다.
### 가설 9:  FA선수가 되어 연봉이 오른 선수의 경우 차기 년도 성적이 좋을 것이다.

- ERA (평균 자책점) : 투수가 한 게임 (9이닝)당 내준 평균 자책점을 의미한다.
- FIP (수비 무관 평균 자책점) : 수비의 도움이 없이, 온전히 투수가 한 게임 (9이닝)당 내준 평균 자책점을 의미한다.
- WAR (대체 선수 승리 기여도) : 선수가 팀 승리에 얼마나 공헌하였는가를 종합하여 표현하는 스탯이다. 이 지표의 값은 팀의 승수를 의미한다.
    - 예를 들어, A 선수의 WAR이 3이라면 팀은 50승을 할 수 있었지만, 이 선수가 있어 53승을 할 수 있었다. 라는 의미가 된다.
- 투수는 ERA, FIP, 종합 WAR / 야수는 종합 WAR를 사용하여, 성적을 판단.
    - 결과
        - 투수
            - ER
                
                ![FA 계약 후 연봉 증가율 vs ERA 변화.png](attachment:cbb33472-3b32-4a71-83f4-b5a8a2b5026c:FA_계약_후_연봉_증가율_vs_ERA_변화.png)
                
                ![ERA 성과평가별 선수 수.png](attachment:40da7665-6e88-4bf0-a5b2-8379f13ba148:ERA_성과평가별_선수_수.png)
                
            - FIP
                
                ![FA 계약 후 연봉 증가율 vs FIP 변화.png](attachment:dccfc1b2-6067-4234-80b6-ccdbd78dd8e8:FA_계약_후_연봉_증가율_vs_FIP_변화.png)
                
                ![FIP 성과평가별 선수 수.png](attachment:3c4ad49d-182a-4cf5-81b2-85c221e3a538:FIP_성과평가별_선수_수.png)
                
            - 종합 WAR
                
                ![FA 계약 후 연봉 증가율 vs WAR 변화.png](attachment:d79daef2-8aac-46d0-b4b7-fae47ec32f9a:FA_계약_후_연봉_증가율_vs_WAR_변화.png)
                
                ![선수별 WAR당 연봉 변화.png](attachment:7b4d6168-d549-407f-8b21-2acd018a8f25:선수별_WAR당_연봉_변화.png)
                
                ![WAR 성과평가별 선수 수.png](attachment:d18c623e-35d5-4e3d-afe4-8463373b02fe:WAR_성과평가별_선수_수.png)
                
            - WAR 향상 인원 중 연봉 향상도
            
            ![WAR 향상 선수의 WAR 향상도 및 연봉 변화.png](attachment:339da522-7fea-4cee-af55-ef6e647c995e:WAR_향상_선수의_WAR_향상도_및_연봉_변화.png)
            
            - 연봉 증가와 성적 지표 변화 간의 상관관계
            
            ![연봉 증가와 성적 지표 변화간의 상관관계.png](attachment:5f26ba49-2dc3-4140-99e8-9a17865372a5:연봉_증가와_성적_지표_변화간의_상관관계.png)
            
            - 피어슨 상관계수의 p-value 결과
            
            ![image.png](attachment:79c68647-b2e4-4015-92d4-d2ab6690555e:image.png)
            
            ![image.png](attachment:743d2c45-a318-4cd6-a2fe-bd9c788a8e4c:image.png)
            
        - 야수
            - 종합 WAR
                
                ![FA 계약 후 연봉증가율 vs WAR 변화.png](attachment:397cffb2-f311-47df-94e1-91e5b5c1e8f2:FA_계약_후_연봉증가율_vs_WAR_변화.png)
                
                ![선수별 WAR당 연봉 변화.png](attachment:d71e49c2-c09d-4db2-be1e-5a2b046c2e2b:선수별_WAR당_연봉_변화.png)
                
                ![성과평가별 선수 수.png](attachment:9eb41068-f68a-4591-bc15-40e82b043453:성과평가별_선수_수.png)
                
            - WAR 향상 인원 중 연봉 향상도
                
                ![FA 계약 후 WAR가 향상된 선수들의 연봉 변화.png](attachment:a4ebf608-2a7a-4ba3-aeb7-1005177ec243:FA_계약_후_WAR가_향상된_선수들의_연봉_변화.png)
                
                ![WAR 향상 선수의 WAR 향상도 및 연봉 변화.png](attachment:5ea83728-96ab-46d3-86a9-fec1e051f9fc:WAR_향상_선수의_WAR_향상도_및_연봉_변화.png)
                
                ![성과평가별 선수 수.png](attachment:1fe6b569-cfdd-4d15-8d9d-261fbe6c06b3:성과평가별_선수_수.png)
                
            
            - 연봉 증가와 성적 지표 변화 간의 상관관계
                
                ![연봉 증가와 성적 지표 변화 간의 상관관계.png](attachment:4334a9a1-f67f-4ed8-b6d0-56c33a8b9d21:연봉_증가와_성적_지표_변화_간의_상관관계.png)
                
            
            - 피어슨 상관계수의 p-value 결과
                
                ![image.png](attachment:71dfe1ef-e912-4083-bf51-25c9d2a0b90f:image.png)
                
        
        ⇒ 투수, 야수 모두 성적과 관련하여 귀무가설이 채택되어, FA 선수가 되어 연봉이 오른 선수의 경우 차기 년도 성적이 좋을 것이다 라는 가설은 틀리게 됩니다. 
        
        ⇒ 아마 FA 금액이 오른 선수들은 성적을 제외하고도, 여러 가지 복합 요인들로 인하여, FA 가격이 예상보다 오르게 되었고, 각 해의 컨디션에 따라 성적이 좌지우지 된다. (부상 포함)
        
## 가설 11. 교타자 보다 중장거리 타자 혹은 거포 타자가 FA 금액을 많이 받을 것이다.

- 가설 11. 교타자보다 중장거리형 타자 혹은 거포형 타자가 FA 금액을 더 많이 받을 것이다.
    - 의미 설명
        - 교타자 (Contact hitter)
            - 장타보다는 단타를 많이 노리는 선수 or 정확하게 치는 선수 혹은 의도적으로 그렇게 치는 선수
        - 중장거리형 타자 (Power hitter)
            - 홈런보다는 2루타 등 장타를 많이 때려낼 수 있는 타자.
        - 거포형 타자 (Slugger)
            - 장타자. 홈런을 많이 때려낼 수 있는 선수
        - [OBP (출루율)](https://library.fangraphs.com/offense/obp/)
            - 타자가 출루를 얼마나 했는지 확인하는 지표
        - [ISO (순장타율)](https://library.fangraphs.com/offense/iso/)
            - 장타율에서 타율을 뺀, 장타만을 확인할 수 있는 지표
        - [wRC+ (조정 득점 창출력)](https://library.fangraphs.com/offense/wrc/)
            - 선수의 전반적인 공격 기여도를 보는 스탯이다. (기준을 100으로 두며, 115이면, 평균적인 타자들보다 15% 더 득점에 기여했다는 것을 의미)
        
    - 전처리
        - 각 시즌 평균 스탯에 대한 CSV 파일을 가지고 와, 해당 선수가 활약한 해와 결합하여, 비교 후, 스탯-평균 ⇒ DIFF 칼럼을 생성.
        - diff 칼럼을 통해, 각 시즌에 대한 값 비교 (타고투저 / 투고타저를 위하여 비교함)
        - 이후, FA 전 4년 간의 기록을 가중치로 두어, FA 직전일 수록 가중치를 높여, 계산하였음.
        - 이에 가중치 DIFF 칼럼으로 바꾸어, 해당 선수의 기록을 한 행으로 나타냄.
        - 아래의 기준을 통해, 교타자 / 중장거리형 타자 / 거포형 타자를 구분하였음.
        - 유형 기준
            1. 교타자
                - AVG_diff : 시즌 평균 + 0.02 이상
                - OBP_diff : 시즌 평균 + 0.02 이상
                - ISO_diff : 시즌 평균 -0.02 이상 + 0.03 미만
                - wRC+ : 85 이상
            2. 중장거리형 타자
                - AVG_diff : 시즌 평균 - 0.005 이하
                - OBP_diff : 시즌 평균 + 0.01 이상
                - ISO_diff : 시즌 평균 + 0.03 이상 0.06 미만
                - wRC+ : 95 이상
            3. 거포형 타자
                - AVG_diff : 시즌 평균 - 0.03 이상
                - OBP_diff : 시즌 평균 + 0.01 이상
                - ISO_diff : 시즌 평균 + 0.06 이상
                - wRC+ : 120 이상
        - 각 유형별 결과
            1. 교타자
                
                ![교타자 AVG vs OBP.png](attachment:653431f6-e532-4e01-adfc-510bb9b3f2ec:교타자_AVG_vs_OBP.png)
                
                ![교타자 FA & wRC+.png](attachment:e532ec90-385e-4943-bb58-246115b83118:교타자_FA__wRC.png)
                
            
            1. 중장거리형 타자
                
                ![중장거리형 타자 AVG vs OBP.png](attachment:ad8a3b91-dd0b-431a-b324-6d228b05316a:중장거리형_타자_AVG_vs_OBP.png)
                
                ![중장거리형 타자 FA & wRC+.png](attachment:e4f2492f-e771-4ac0-a142-9eb472f9869a:중장거리형_타자_FA__wRC.png)
                
            
            1. 거포형 타자
                
                ![거포형 타자 AVG vs OBP.png](attachment:e79d5e0f-b732-4547-aebd-d27b5e9fdacf:거포형_타자_AVG_vs_OBP.png)
                
                ![거포형 타자 FA & wRC+.png](attachment:f9ca030d-6ef6-400d-84bc-fa5ac5fec657:거포형_타자_FA__wRC.png)
                
        
        ![FA 선수 유형별 비율.png](attachment:ea572a3d-6eb9-4526-9c43-8e79f144afd6:FA_선수_유형별_비율.png)
        
        ![FA 선수 유형별 평균 계약 총액과 년수 비교.png](attachment:23e9b9ba-9b56-44cd-97a2-7f2d82fb4d32:FA_선수_유형별_평균_계약_총액과_년수_비교.png)
        
        - 정규성 검정 시행 후, 등분상 가정을 사용하였을 때, 0.0377로 0.05 이하이기에, 귀무가설을 기각하여, 해당 가설이 통계적으로 옳음을 나타내었다.
        
        ![가설 검정(등분산 가정).png](attachment:c5ed556a-b1f5-4b55-83f7-3828428f2a6a:가설_검정(등분산_가정).png)
        
        ![교타자 VS 중장거리형 타자와 거포형 타자 FA 계약 총액 분포.png](attachment:67ddb4d4-f98d-4fca-95f2-9b72c2f5c0ec:교타자_VS_중장거리형_타자와_거포형_타자_FA_계약_총액_분포.png)
        
    
    - 코드를 적기엔 너무 많아, 링크를 첨부
        - [Code (Colab)](https://colab.research.google.com/drive/1gMtw9l-_hTc4Zn2OEPP7mkeVSUo_o20e?usp=sharing)