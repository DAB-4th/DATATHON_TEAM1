# DATATHON_TEAM1

## 목차 (가설 3개 설정)
1. [가설 3 - 기각](https://github.com/DAB-4th/DATATHON_TEAM1/tree/%ED%91%9C%EB%A3%A1%ED%9D%AC?tab=readme-ov-file#%EA%B0%80%EC%84%A4-3-%EA%B5%AC%EC%9B%90-%ED%88%AC%EC%88%98%EC%9D%BC%EB%AA%85-%EB%B6%88%ED%8E%9C-%ED%88%AC%EC%88%98%EB%8A%94-%EB%8B%A4%EB%A5%B8-%ED%8F%AC%EC%A7%80%EC%85%98%EC%97%90-%EB%B9%84%ED%95%B4-fa-%EA%B0%80%EA%B2%A9%EC%9D%B4-%EB%82%AE%EC%9D%84-%EA%B2%83%EC%9D%B4%EB%8B%A4)
2. [가설 9 - 채택](https://github.com/DAB-4th/DATATHON_TEAM1/tree/%ED%91%9C%EB%A3%A1%ED%9D%AC?tab=readme-ov-file#%EA%B0%80%EC%84%A4-9-fa%EC%84%A0%EC%88%98%EA%B0%80-%EB%90%98%EC%96%B4-%EC%97%B0%EB%B4%89%EC%9D%B4-%EC%98%A4%EB%A5%B8-%EC%84%A0%EC%88%98%EC%9D%98-%EA%B2%BD%EC%9A%B0-%EC%B0%A8%EA%B8%B0-%EB%85%84%EB%8F%84-%EC%84%B1%EC%A0%81%EC%9D%B4-%EC%A2%8B%EC%9D%84-%EA%B2%83%EC%9D%B4%EB%8B%A4---%EC%B1%84%ED%83%9D)
3. [가설 11 - 채택]()

* [수정사항](https://github.com/DAB-4th/DATATHON_TEAM1/tree/%ED%91%9C%EB%A3%A1%ED%9D%AC?tab=readme-ov-file#%EC%88%98%EC%A0%95%EC%82%AC%ED%95%AD)
- - -
## 가설 3: 구원 투수(일명 불펜 투수)는 다른 포지션에 비해 FA 가격이 낮을 것이다. - (기각)
### 가설 3: 구원 투수(일명 불펜 투수)는 다른 포지션에 비해 FA 가격이 낮을 것이다. - (기각)

- 구원 투수 포지션 : RP (중간 계투), CP (마무리 투수)
    - 선발 투수 포지션 : SP
- 각 포지션 별 FA 금액의 평균을 사용
    - 모든 포지션과 불펜 투수 내에서도 세부 포지션을 나누어, 각 포지션 별 FA 금액 평균을 구분
    - 불펜 투수(RP, CP) 그룹과 이외 그룹으로 나누어, 그룹별 FA 금액 평균을 구분
        - 실제 금액 차이
            - 포지션당 평균  FA 금액
            
            ![포지션당 평균 FA 금액 (막대)](https://github.com/user-attachments/assets/e51d8bf4-d928-48bf-91ac-bf2fd77d0195)        

            ![포지션당 평균 FA 금액 (Box Plot)](https://github.com/user-attachments/assets/877a2697-b115-45da-a34b-20d3f11a8f3d)

                - ANOVA 검정 시행
          
                  ![포지션당 평균 FA 금액_ANOVA 검정](https://github.com/user-attachments/assets/5abcfe67-0b3c-4ddc-b728-30ea9eedf8ab)
            
            - 불펜 그룹과 이외 그룹
            
            ![불펜 그룹과 이외 그룹의 평균 FA 금액 (막대)](https://github.com/user-attachments/assets/181f0b54-4459-40e6-94e3-01b0f7474be1)

            ![불펜 그룹과 이외 그룹의 평균 FA 금액 (Box Plot)](https://github.com/user-attachments/assets/1ba1fdaf-f0d9-494c-b83c-e1d6291342a6)

                - T-검정 시행
        
                  ![불펜 그룹과 이외 그룹_T 검정](https://github.com/user-attachments/assets/b583986a-ceb2-4d3d-b059-fb831ce5f16f)

            
            ⇒ 불펜이 확실하게 FA 금액을 적게 받는 영향이 있다.
            
            → 확실히, FA 까지 가게 된 선수의 경우, 필승조(의 역할을 많이 보여주고 있기 때문에, 많은 등판, 많은 이닝을 소화하게 된다. 
            
            → 이 때문에, 몸에 부하가 많이 쌓인 상태이며, FA 이후 시즌의 부상의 위험이 크기 때문에, 이를 고려하여, FA 금액이 작아질 수 밖에 없다.
            
            - CP(마무리 투수)의 경우는, 나올 수 있는 상황이 제한되어 있고, 고정적인 이닝에 등판할 가능성이 높아, 관리가 매우 원활하다.
            
            → 따라서, 부상의 위험이 불펜 투수들보다는 훨씬 덜 하고, 마무리 투수의 보직 자체가 리그에서 가장 강력한 투수를 마지막에 사용하기 때문에, FA 금액이 올라갈 수 밖에 없다.

- - -

## 가설 9. FA선수가 되어 연봉이 오른 선수의 경우 차기 년도 성적이 좋을 것이다. - (채택)
### 가설 9:  FA선수가 되어 연봉이 오른 선수의 경우 차기 년도 성적이 좋을 것이다. - (채택)

- ERA (평균 자책점) : 투수가 한 게임 (9이닝)당 내준 평균 자책점을 의미한다.
- FIP (수비 무관 평균 자책점) : 수비의 도움이 없이, 온전히 투수가 한 게임 (9이닝)당 내준 평균 자책점을 의미한다.
- WAR (대체 선수 승리 기여도) : 선수가 팀 승리에 얼마나 공헌하였는가를 종합하여 표현하는 스탯이다. 이 지표의 값은 팀의 승수를 의미한다.
    - 예를 들어, A 선수의 WAR이 3이라면 팀은 50승을 할 수 있었지만, 이 선수가 있어 53승을 할 수 있었다. 라는 의미가 된다.
- 투수는 ERA, FIP, 종합 WAR / 야수는 종합 WAR를 사용하여, 성적을 판단.
    - 결과
        - 투수
            - ERA
                
                ![FA 계약 후 연봉 증가율 vs ERA 변화](https://github.com/user-attachments/assets/a0efacdd-0f49-4742-84e0-9836945bf19a)
                
                ![ERA 성과평가별 선수 수](https://github.com/user-attachments/assets/958170f1-f578-4361-bfa1-dbf4bdfda2de)

                
            - FIP
                
                ![FA 계약 후 연봉 증가율 vs FIP 변화](https://github.com/user-attachments/assets/0113ed96-8547-43fc-9ea5-dacc52ca57d5)

                ![FIP 성과평가별 선수 수](https://github.com/user-attachments/assets/c1ec80b8-4db7-400c-b8c1-b1e4e8895ae2)

                
                
            - 종합 WAR
                
                ![FA 계약 후 연봉 증가율 vs WAR 변화](https://github.com/user-attachments/assets/f9c51f07-b18b-4b5b-bedd-1886b504ddad)

                ![선수별 WAR당 연봉 변화](https://github.com/user-attachments/assets/9a40010a-b0f0-43b7-96e0-a25db0d782c3)

                ![WAR 성과평가별 선수 수](https://github.com/user-attachments/assets/ef1ae7d3-66bb-406a-994b-8d7115c33714)

          
            - WAR 향상 인원 중 연봉 향상도
            
            ![WAR 향상 선수의 WAR 향상도 및 연봉 변화](https://github.com/user-attachments/assets/c028e7fc-6c6c-48fa-93b0-fdb861edd010)

            
            - 연봉 증가와 성적 지표 변화 간의 상관관계
            
            ![연봉 증가와 성적 지표 변화간의 상관관계](https://github.com/user-attachments/assets/6f574ae2-1c5e-4f44-ad08-bf9dac07fde3)

            - 피어슨 상관계수의 p-value 결과
            
            ![피어슨 상관계수의 p-value 결과](https://github.com/user-attachments/assets/1f3c13a8-21fc-46fa-9af1-1667893db6c5)

            
        - 야수
            - 종합 WAR
                
                ![FA 계약 후 연봉증가율 vs WAR 변화](https://github.com/user-attachments/assets/9267d78b-d5d5-4a67-85a4-3d89fd17c1eb)

                ![선수별 WAR당 연봉 변화](https://github.com/user-attachments/assets/1ebff206-128f-45a1-8263-e861391fbae8)

                ![성과평가별 선수 수](https://github.com/user-attachments/assets/ca956166-b8a6-4765-ae10-a03fa5dca26d)

            - WAR 향상 인원 중 연봉 향상도
                
                ![FA 계약 후 WAR가 향상된 선수들의 연봉 변화](https://github.com/user-attachments/assets/cedef433-c9cf-4d4c-9cf3-de5cdd804baa)
                
                ![WAR 향상 선수의 WAR 향상도 및 연봉 변화](https://github.com/user-attachments/assets/050ff164-cdbf-42f5-be43-86e38152c7cc)
                
            - 연봉 증가와 성적 지표 변화 간의 상관관계
            - 
                ![연봉 증가와 성적 지표 변화 간의 상관관계](https://github.com/user-attachments/assets/e31ddede-0983-4b10-93d6-d1ce80e7092d)                
            
            - 피어슨 상관계수의 p-value 결과

                ![피어슨 상관계수의 p-value 결과](https://github.com/user-attachments/assets/762f03f5-ced2-44a1-9614-72f2ad8bba49)
                
        ⇒ 투수, 야수 모두 성적과 관련하여 귀무가설이 채택되어, FA 선수가 되어 연봉이 오른 선수의 경우 차기 년도 성적이 좋을 것이다 라는 가설은 틀리게 됩니다. 
        
        ⇒ 아마 FA 금액이 오른 선수들은 성적을 제외하고도, 여러 가지 복합 요인들로 인하여, FA 가격이 예상보다 오르게 되었고, 각 해의 컨디션에 따라 성적이 좌지우지 된다. (부상 포함)

- - - 
## 가설 11. 교타자 보다 중장거리 타자 혹은 거포 타자가 FA 금액을 많이 받을 것이다. - (채택)
### 가설 11. 교타자보다 중장거리형 타자 혹은 거포형 타자가 FA 금액을 더 많이 받을 것이다. - (채택)

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
           
            ![교타자 AVG vs OBP](https://github.com/user-attachments/assets/34782107-b04f-4834-b696-d75a97bef11b)

            ![교타자 FA & wRC+](https://github.com/user-attachments/assets/25938092-5b81-4042-be3a-68097b56e19d)

        2. 중장거리형 타자
                
            ![중장거리형 타자 AVG vs OBP](https://github.com/user-attachments/assets/f114667a-48a7-4c12-9da0-77aff5c4c3c8)

            ![중장거리형 타자 FA & wRC+](https://github.com/user-attachments/assets/fb13ff04-85fe-45c4-9300-40f48845122a)

            
        3. 거포형 타자
                
           ![거포형 타자 AVG vs OBP](https://github.com/user-attachments/assets/cff860be-bf54-467e-8105-b6888e441e43)

           ![거포형 타자 FA & wRC+](https://github.com/user-attachments/assets/9320f785-b162-4d0b-adcc-73da7bdcd078)

  ![FA 선수 유형별 비율](https://github.com/user-attachments/assets/5b75994c-4a67-41cd-a1ba-d48b85fe37b5)
        
  ![FA 선수 유형별 평균 계약 총액과 년수 비교](https://github.com/user-attachments/assets/96a04018-aba5-42a7-9a2b-c8bfb46ef61b)
 
  ![교타자 VS 중장거리형 타자와 거포형 타자 FA 계약 총액 분포](https://github.com/user-attachments/assets/4127c577-810d-400f-8f61-a093957b5d7b)
      
  - 정규성 검정 시행 후, 등분상 가정을 사용하였을 때, 0.0377로 0.05 이하이기에, 귀무가설을 기각하여, 해당 가설이 통계적으로 옳음을 나타내었다.
        
  ![가설 검정(등분산 가정)](https://github.com/user-attachments/assets/00dac4d6-bbd8-44d7-b94f-a6c1c4d26d47)

- - -


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
    
    - 코드를 적기엔 너무 많아, 링크를 첨부
        - [Code (Colab)](https://colab.research.google.com/drive/1gMtw9l-_hTc4Zn2OEPP7mkeVSUo_o20e?usp=sharing)
