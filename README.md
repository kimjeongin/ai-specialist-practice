### 시험 안내

- 출제 범위
  - 과목 전 과목: LLM, RAG, Data, Vision, On-device
  - 과목 별 실습 교안 기반 출제

- 문항 수
  - 12문항 내외

- 문제 유형
  - 코드 빈칸('### 작성 필요 ###') 채우기
  - 핵심 부분 출제
  - 실습 코드에서 빈칸이 아니였던 곳도 출제 가능
  - 한줄도 있고 여러줄도 있을 수 있다.
  - 실습 코드를 변형하지 않고 그대로 사용하며 코드 빈칸만 만들어서 나온다.

- 문제 참고사항
  - 각 분야 2-3문제
  - 조커 문제는 없다.
  - 난이도 쉬울 예정
  - on-device 혹은 data에 문제가 좀 더 나올 수 있다.
  - vision 문제는 조금 비중이 적을 수 있다.

- 문제 예시
```
[문제]
Q A-1) gemma-2b 모델의 토크나이저를 불러옵니다.

[요구사항]
- BASE_MODEL 사용

[코드]
from transformers import AutoTokenizer

BASE_MODEL = "google/gemma-2b"

tokenizer = ### 작성 필요 ###
```

- 문제에 제공되는 레퍼런스
  - 과목 별 강의 및 실습 교안
  - 문제 정답에 해당하는 부분 마스킹 ('### 공개 제한 ###') 됨

```
---
1. Foundation Model: gemma-2b

Instruction & Preference Fine-Tuning이 되지 않은 Base Gemma-2B 모델에서의 결과를 먼저 확인해 보겠습니다.
---

# BASE_MODEL = "google/gemma-2b"
Base_Model = "djfkla"

# 사전 학습된 'google/gemma-2b' 모델과 토크나이저를가져옵니다.
model = ### 공개 제한 ###

tokenizer = ### 공개 제한 ###
```

