## 기본적인 틀을 제공하며, 파일이나 폴더를 수정/업로드하여 사용합니다.
# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정서연
- 리뷰어 : 김민혁


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/d2007f01-75ec-450b-a15a-200d6a2ce28f)

    ![image](https://github.com/user-attachments/assets/23ab9b92-b7cf-4e89-9c3a-8426d3633fdd)

    ![image](https://github.com/user-attachments/assets/265e2aff-ea17-4ff8-b1fd-ed9682e5fb7f)

    > Train, 파인튜닝, bucketing 방식 모두 정상적으로 구현하고 실행하셨고, 구성 방식에 따른 결과값도 잘 표기해주셨습니다.
    
    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/95bc15cb-cc10-44ed-a7b6-fc4a1b6b4924)

    ![image](https://github.com/user-attachments/assets/ffd9ece7-9bb1-4550-b5fb-f435c64e3dc4)

    > 데이터를 잘 살펴보고 중복되는 데이터나, 데이터의 특성을 파악해 글자 수에 따른 결과만을 정제하신 부분이 인상깊었습니다. 왜 하셨는지 주석 설명과 그래프 시각화로 의미가 잘 전달되었어요
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/f4115ad8-ce8a-4e99-91d0-cd22e8e7b2f5)

    ![image](https://github.com/user-attachments/assets/ec79290a-10a4-4a6a-ae50-ba70a1766e40)

    > 여러가지 실험을 통해 결과의 성능을 높이고자 다양한 시도를 하셨습니다. 특히, 모델의 하위 절반 레이어를 동결시키는 방식까지 접근하시는 방법은 새로웠습니다!
             
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
     
    ![image](https://github.com/user-attachments/assets/4c693c3d-2071-4452-86a3-d477200578aa)

    > 훈련 시간이 길었음에도 불구하고 여러가지 실험을 하신 면이 좋았습니다!
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부

    ![image](https://github.com/user-attachments/assets/40ecc32a-b87d-4eb7-82f9-4efeb5aafc7f)

    > Custom Callback이나 transform 함수 등 코드를 효율적으로 활용하시고 정의하신 부분이 좋았습니다

# 회고(참고 링크 및 코드 개선)
```
처음에 서연님이 huggingface 데이터셋임에도 불구하고 잘 탐구하시고 정제하시는 부분에서 놀라웠습니다.
데이터의 접근 본질을 까먹고 있다가 절 일깨워주셨어요 ㅎㅎ
워낙 커스텀이 잘 되있는 허깅페이스 데이터셋이라 생각해서 안일했었는데, 성능을 높이기 위해
전처리나 여러가지 실험을 진행한 면이 굉장히 열정적인 모습으로 높게 봤습니다! 수고하셨어요
```

