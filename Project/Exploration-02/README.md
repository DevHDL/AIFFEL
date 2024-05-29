🔑 **PRT(Peer Review Template)**
 Reviewer : 맹주현 
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    - 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, 퀘스트 문제 요구조건 등을 지칭
    - 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
     
![화면 캡처 2024-05-29 170649](https://github.com/DevHDL/AIFFEL/assets/168398983/1776067f-7d0e-4596-a25c-1595fdad86fd)
![화면 캡처 2024-05-29 170830](https://github.com/DevHDL/AIFFEL/assets/168398983/b6d6bc72-e730-48c5-891a-eb240ed2f97a)
![화면 캡처 2024-05-29 170921](https://github.com/DevHDL/AIFFEL/assets/168398983/95e21db4-1df6-4359-87bb-d69923f70e75)


- [X]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)**
    - [X]  모델 선정 이유
        {'XGBRegressor': 148585.85336648213, 'LGBMRegressor': 134408.95208988542}
          기본적인 모델을 돌려봤을 때, LGBM이 성능이 좋아서 LGBM을 선택 
    - [X]  Metrics 선정 이유
    - [X]  Loss 선정 이유

- [X]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)**
    - [X]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)
    - [X]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
    - [X]  각 실험을 시각화하여 비교하였나요?
    - [X]  모든 실험 결과가 기록되었나요?

![화면 캡처 2024-05-29 172055](https://github.com/DevHDL/AIFFEL/assets/168398983/0d808e0f-b6a7-4307-95f0-e7f5b7ebba60)
![화면 캡처 2024-05-29 172037](https://github.com/DevHDL/AIFFEL/assets/168398983/27a11773-d627-4808-8f27-6e8021ecc8f3)
![화면 캡처 2024-05-29 172016](https://github.com/DevHDL/AIFFEL/assets/168398983/327dd716-49f2-4766-8060-e5eb2b4b036e)

Price와 상관관계가 높은 데이터만 훈련시키기 -> 여러 테스트를 수행하고 성능 비교까지 시간 내에 성공적으로 하셨네요.

- [X]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)**
    - [X]  배운 점
    - [X]  아쉬운 점
    - [X]  느낀 점
    - [ ]  어려웠던 점
     
![화면 캡처 2024-05-29 171017](https://github.com/DevHDL/AIFFEL/assets/168398983/9e76da9d-5f6d-4c12-9025-8336977f25f5)
![image](https://github.com/DevHDL/AIFFEL/assets/163500244/83e20781-2a61-4101-ab16-d1090a20b466)

딱히 어려움을 느끼지 않으셨나 봅니다. :thumbsup:

내가 배운 것
train = pd.get_dummies(train, columns=['year'])

list(train.columns) == list(test.columns)
True
