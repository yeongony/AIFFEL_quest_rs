## 기본적인 틀을 제공하며, 파일이나 폴더를 수정/업로드하여 사용합니다.
# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 정서연
- 리뷰어 : 김소희


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었습니다.
        - ![image](https://github.com/user-attachments/assets/218da980-d8af-4f0b-8b9d-3aadb58ec7f8)
        - ![image](https://github.com/user-attachments/assets/d0a5dc27-bc46-4d28-a3c3-69bfc9e925cc)

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 전체적으로 주석이 없습니다. 코드를 이해하기 쉽도록 주석을 달아 주시면 좋겠습니다.
    - 주석이 필요하다고 생각하는 부분 : ![image](https://github.com/user-attachments/assets/8c0c41d9-736f-4e35-96f1-afc5b758b740) 모델의 핵심 함수 부분이기 때문에 계산 과정을 말로 풀어서 설명하면 좋을 듯합니다. ![image](https://github.com/user-attachments/assets/94227f6f-45d8-444b-916f-837de469832c) to_datetime 함수가 어떤 자료형을 리턴하는지 등을 적어 주시면 좋을 듯합니다.

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정이 잘 나타나 있지 않습니다.
    - 추가적으로 lr, epoch 등을 변경하여 실험했는지 그 과정이 나타나 있지 않습니다. 다양한 hyperparameter를 적용하는 과정을 코드로 보여 주면 좋겠습니다.

        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 프로젝트 회고가 적혀 있지 않습니다. 잘했던 점, 아쉬운 점 등을 적어 주세요.
    - 전체 코드 실행 플로우를 그래프로 그리거나 수치로 표시하여 이해를 돕고 있습니다.
        - ![image](https://github.com/user-attachments/assets/c0199698-6bf6-43f8-b1b1-2f937598b0d4) : 데이터의 shape을 한 번 표시하여 데이터를 이해하기 쉽게 만들었습니다.
        - ![image](https://github.com/user-attachments/assets/9441f34f-a35f-4bd3-982a-cb71028c4ad9) : 각 iteration에서의 loss를 프린트하여 loss 변화를 한 번 인식할 수 있게 했습니다.
        - ![image](https://github.com/user-attachments/assets/66b1e553-d53c-4ec9-afe2-7907d357656b) : 모델 학습 후 최종 weight와 bias를 표시하여 모델의 전체적인 경향성을 보여주었습니다.

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했습니다.
        - ![image](https://github.com/user-attachments/assets/2b9ae92d-9206-48af-9566-3bb32ec03469) 자주 사용되는 수식 등을 함수로 만들었습니다.
        - ![image](https://github.com/user-attachments/assets/5eb65e25-fafb-4a61-8bc0-bfef11ed0c2c) data를 copy하는 과정이 불필요하다고 생각됩니다. 데이터 시각화를 위해 넣으신 것 같은데, 두 항을 따로 입력해도 시각화할 수 있습니다.




# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고 : 깔끔하고 올바른 결과가 나왔지만, 주석이 없어 코드의 의미가 불분명한 부분들이 있었습니다. 첫 리뷰라 개선할 점을 찾는 것이 생각보다 어려웠습니다.
# 수정하고 싶은 부분 : 
![image](https://github.com/user-attachments/assets/c6db0e91-e2f4-48c0-bb40-9a5648c44bd6) : 모델 학습 전이므로 gradient 함수가 잘 계산되는지 확인하는 것 이외에는 의미가 없습니다. 모델 학습 이후로 코드 위치를 바꾸거나, 삭제해도 될 것 같습니다.

```
`
