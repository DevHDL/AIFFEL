🔑 **PRT(Peer Review Template)**

- [o] **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**

  - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
  - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개,
    퀘스트 문제 요구조건 등을 지칭 - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부

![](https://github.com/DevHDL/AIFFEL/blob/main/Project/Exploration-04/prt_review_images/01.png)
![](https://github.com/DevHDL/AIFFEL/blob/main/Project/Exploration-04/prt_review_images/02.png)
![](https://github.com/DevHDL/AIFFEL/blob/main/Project/Exploration-04/prt_review_images/03.png)
![](https://github.com/DevHDL/AIFFEL/blob/main/Project/Exploration-04/prt_review_images/04.png)
![](https://github.com/DevHDL/AIFFEL/blob/main/Project/Exploration-04/prt_review_images/06.png)

- [o] **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**

  - [ ] 모델 선정 이유
  - [ ] Metrics 선정 이유
  - [ ] Loss 선정 이유
  - **위 3개는 시간 관계상 직접 모델을 학습하지 않고 학습된 모델을 사용함**
  - 대신 직접 클래스를 구현해서 만든코드에 각각 어떤기능인지에 대한 주석들이 써져있음

![](https://github.com/DevHDL/AIFFEL/blob/main/Project/Exploration-04/prt_review_images/05.png)

- [o] **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**

  - [ ] 데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
  - [ ] 하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
  - **위 2개는 시간 관계상 직접 모델을 학습하지 않고 학습된 모델을 사용함**
  - [o] 각 실험을 시각화하여 비교하였나요?
  - [o] 모든 실험 결과가 기록되었나요?
  - 각 실험마다 시각화아였고, 결과가 기록되어있음

- [o] **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
  - [o] 배운 점
    - Semantic Segmentation을 하는 실습
  - [0] 아쉬운 점
    - 패딩을 입고 찍은 사진에서 패딩까지 같이 블러처리가 되어서 cv2.GaussianBlur()를 쓰면 좀더 부드럽게 될거같아서 이와 관련된 내용을 찾고, 정리해 두셨슨데 시간이 모자라서 못하셨다고 한다
  - [0] 느낀 점
    - 현업에서는 method, class를 자주 활용할 것이라 생각하셔서 이번엔 class로 작성하셨다는 회고를 작성해주셨다
  - [0] 어려웠던 점
    - 어떻게 사람이 여러명 있는 사진에서의 Semantic Segmentation을 좀더 자연스럽게 처리할 수 있는지
