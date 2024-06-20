### 06.20 코드 리뷰
***
### 코더 : 이현동님
### 리뷰어 : 고대현
***
### 리뷰어 총평
순서와 루브릭에 맞게 실험을 진행해주셨습니다.

다양한 하이퍼파라미터 시도와 epoch 학습 과정을 시각화 하신 것이 인상 깊었습니다.

학습 결과는 아쉽다고 말씀하셨는데, 앞으로 더 나은 모델을 구현하시기를 바라겠습니다.

현동님, 프로젝트 하시느라 고생하셨습니다 :D
***
🔑 **PRT(Peer Review Template)**

- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
        - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
    > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/ad8992df-2285-42be-ac8d-b2a12509c294)
    > 데이터 불러오기, 데이터 전처리, Subword Text Encoder, 모델 구성 등을 상세히 기록하고 구현해주셨습니다.
    > 구현한 한국어 트랜스포머 모델이 병렬 데이터 학습 시 안정적으로 수렴하였습니다.
    > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/66abcfbc-00f5-4004-b748-ae60e99deffd)
    > 한국어 입력 문장에 맞는 출력 문장을 작성하셨습니다.
    > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/95ebab22-41a6-4ab0-9ccb-1508f665f3e5)



- [X]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
      > 핵심적인 부분에 대해 마크다운 형태로 잘 적어주셨지만, 모델, metrics, loss 선정 이유에 대해서는 적어주시지 않았습니다.
    - [ ]  모델 선정 이유
    - [ ]  Metrics 선정 이유
    - [ ]  Loss 선정 이유

- [ ]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [ ]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
      > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/bcb01a64-00d4-4ffe-9aa0-7d86114805f2)
      > question, answer로 구분하셨습니다 :D
    - [ ]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
      > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/9f4169c3-5935-4ade-b661-1255aaa48fc8)
      > 하이퍼라미터를 변경해가며 여러 시도를 하셨습니다!
    - [ ]  각 실험을 시각화하여 비교하였나요?
      > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/7482a599-46d3-4ce7-8e24-a51e6c78e27b)
      > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/ea100275-1625-4830-bacb-716c197de7b0)
      > 각 실험 결과를 시각화하여 비교하셨습니다 :)
    - [ ]  모든 실험 결과가 기록되었나요?
      > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/0f06895e-1263-42f3-90eb-1722504cbf14)
      > 모든 실험 결과가 기록되었습니다!

- [X]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
      > ![image](https://github.com/DevHDL/AIFFEL/assets/102419537/808f622a-6781-43b3-9023-3d35099bd471)
      > 프로젝트에 대한 회고에 대해 기록해주셨습니다 :D
    - [X]  배운 점
    - [X]  아쉬운 점
    - [X]  느낀 점
    - [ ]  어려웠던 점
