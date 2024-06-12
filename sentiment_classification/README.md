@@ -1,24 +1,65 @@
## 06.12 코드 리뷰
***
### 코더 : 이승열님
### 리뷰어 : 고대현
***
### 총평
다양한 모델 및 용어로 실험을 진행해주셔서 재밌게 실험 결과를 지켜본 것 같습니다.

실험 결과도 꼼꼼하게 기록되어 있어서, 보기 좋았던 결과를 볼 수 있었던 것 같습니다.

프로젝트 하시느라 수고 많으셨습니다 :D
***
🔑 **PRT(Peer Review Template)**

- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
    퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부

![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/19d799a5-bc5f-4c69-87cb-f6c6aab9feb9)
> 3가지 이상의 모델이 성공적으로 시도됨
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/ee414baf-87ed-4e86-a461-f6104b3b7382)
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/a548185c-a45d-4687-a2c5-b2bd56a241d1)
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/5f9797a0-10c8-45c8-9116-73247a0cd4e3)
> gensim의 유사단어 찾기를 활용하여 자체학습한 임베딩과 사전학습 임베딩을 비교 분석함
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/e46fe442-5e92-43f3-8810-80ead20375be)
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/569aff8d-10ae-4b86-a2bd-1e34aee2363c)
> 네이버 영화리뷰 데이터 감성분석 정확도를 85% 이상 달성함
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/bec168ac-dd28-4bac-aa62-832459543cb3)

- [ ]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
> 다양한 모델을 사용해주셨고, Metrics, Loss에 대해 기록해주셨는데, 선정하신 이유에 대해서는 기록해주시지 않으셨습니다.
    - [ ]  모델 선정 이유
    - [ ]  Metrics 선정 이유
    - [ ]  Loss 선정 이유

- [ ]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [ ]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [ ]  각 실험을 시각화하여 비교하였나요?
    - [ ]  모든 실험 결과가 기록되었나요?

- [ ]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [ ]  배운 점
    - [ ]  아쉬운 점
    - [ ]  느낀 점
    - [ ]  어려웠던 점
- [X]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [X]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
> train, validation, test 데이터로 모두 구분하여 프로젝트를 진행하셨습니다.
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/c6b4d3f2-1e00-4386-a495-7b997a4a2648)
    - [X]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등
> 다양한 epoch, dropout rate를 바탕으로 실험을 진행해주셨습니다.
    - [X]  각 실험을 시각화하여 비교하였나요?
> 각 실험마다 Accuracy와 Loss를 시각화하시고, 이에 대한 이유를 적어주셨습니다.
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/9d32b67d-c1a2-40bb-a5df-e287f82f2331)
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/5dab7a7e-65d2-4376-be18-1dc54255b8fd)
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/5421e763-14b9-4417-b34a-5540902a99a4)
    - [X]  모든 실험 결과가 기록되었나요?
> 모든 실험 결과가 기록되었습니다.
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/c9650ec7-50a5-4a8f-bc21-929e017ab967)
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/5a388dbb-9969-493b-97ff-a89c972a4b2a)



- [X]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
![image](https://github.com/2exponentiation10/aiffel_projects/assets/102419537/e3ed39cb-0feb-4a09-8424-1fad4b89e1ec)
    - [X]  배운 점
  > "회고록 중 / RNN을 제대로 처음 다뤄본것같다. 온전히 내께 된것같지는 않지만 그래도 어떤 흐름으로 진행되고 어떻게 사용하는지 정도는 배운것 같다."
    - [X]  아쉬운 점
  > "회고록 중 / Word2VecKeyedVectors 를 적용하는데 생각보다 시간을 많이 사용해 다양한 값으로 테스트를 진행하지 못한것이 조금 아쉽습니다."
    - [X]  느낀 점
  > "회고록 중 / 역시 기존에 학습된 모델이 성능이 우월하다"
    - [X]  어려웠던 점
  > "회고록 중 / 제공되어 있는 코드를 변환해 작업한 결과 크게 어려움은 느끼지 못했지만, 초반부분에 word_to_index에 있는 패딩을 어떻게 해야할지 찾는데 조금 오래 걸렸습니다. 결국 그냥 설정을 안해도 자동으로 패딩되는걸 찾아 따로 설정하지않고 진행했습니다."
