🔑 **PRT(Peer Review Template)**
> written by 제민욱

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - [x] 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - [x]문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 
        퀘스트 문제 요구조건 등을 지칭
    - [x] 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부

<img width="713" alt="Screenshot 2024-06-20 at 5 37 30 PM" src="https://github.com/minkj1992/aiffel_projects/assets/37536298/106e3f8b-328d-4f46-968c-b89451984b20">

8번의 시도들과, 케라스 튜너를 활용하여 적합한 조합을 찾고자 노력하였으며, 이를 토대로 합리적인 모델을 개발하였음.


- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [x]  모델 선정 이유
    - [ ]  Metrics 선정 이유
    - [ ]  Loss 선정 이유

형태소 분석, subtokenizer등을 비교 분석을 시도하였음.

- [x]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [x]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [x]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [x]  각 실험을 시각화하여 비교하였나요?
    - [x]  모든 실험 결과가 기록되었나요?
    - [ ]  
<img width="720" alt="Screenshot 2024-06-20 at 5 29 08 PM" src="https://github.com/minkj1992/aiffel_projects/assets/37536298/b868628d-faaa-4179-bcb4-19665ab7ba16">
<img width="685" alt="Screenshot 2024-06-20 at 5 29 46 PM" src="https://github.com/minkj1992/aiffel_projects/assets/37536298/a49272ce-d1e7-49cb-a82d-2b12aac0e340">

`from sklearn.model_selection import train_test_split`을 토대로, validation set을 나눴습니다.

케라스 튜너를 활용하여 적합한 하이퍼 파라미터를 search 하였으며, 이를 토대로 적합한 하이퍼파라미터를 탐색해 나갔습니다.
CustomlearningRate을 도입하여 관련된 데이터 셋을 
<img width="400" alt="Screenshot 2024-06-20 at 5 27 49 PM" src="https://github.com/minkj1992/aiffel_projects/assets/37536298/c32731ae-0e8f-4dae-aa2f-ab7df2499ade">

- [x]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [x]  배운 점
    - [x]  아쉬운 점
    - [x]  느낀 점
    - [x]  어려웠던 점

<img width="728" alt="Screenshot 2024-06-20 at 5 24 51 PM" src="https://github.com/minkj1992/aiffel_projects/assets/37536298/c99f0c3c-f588-4087-ba29-04c83c67dd26">

validation set, keras tuner 도입을 통해, 다양한 실험들을 진행한 것이 인상깊었습니다.

<img width="670" alt="Screenshot 2024-06-20 at 5 27 13 PM" src="https://github.com/minkj1992/aiffel_projects/assets/37536298/c028b6f4-4c16-4bee-9554-08dfd94140dc">

