# 2023 한림대학교 ChatGPT 워크샾

## 주제
ChatGPT를 사용한 의학 자료의 QnA 엔진 구현(Implementing Questiong and Answering Engine using ChatGPT)

<br>

## 내용
ChatGPT를 사용하여 2가지 작업을 진행합니다. <br>
<br>
작업1. 네이버지식인의 건강 QnA의 자료를 크롤링하여 이를 ChatGPT로 학습시키고, 건강 질문에 대하여 medical speciality를 예측하도록 합니다.  <br>
작업2. ChatGPT를 가지고 논문과 같은 의학문서에 기반한 QnA엔진을 구축합니다.  <br>
<br>
ChatGPT에 대한 소개와 이를 프로그래밍 언어로 호출하기 위한 OpenAI API를 소개합니다. 더불어 ChatGPT의 한계와 의학적 사용에서의 제약등 기반적인 것도 설명 드립니다. 프로그래밍 코드로 실제 동작하는 시스템을 구축합니다.

<br>

## 목적
의료 현장에 인공지능(AI)을 도입하는 경우가 점점 늘어나고 있으나 국내에는 아직 이 분야를 의학, 간호학 교육에 적용한 예가 많지 않다. 딥러닝 모델 특히 거대자연어모델(Large Language Model)의 경우 환경 구축과 데이터 구축이 어려워 쉽게 접하거나 학습하기가 더욱 어렵다. 최근 ChatGPT가 공개되면서 인공지능의 활용에 대한 다양한 시도와 사례의 소개가 많아지고 있으나 이를 직접 연구와 실무에서의 활용 방법에 대해서는 자료가 많지 않다. ChatGPT를 실제 코드를 사용하여 활용예를 구축함으로서 이런 과정을 이해하기 위한 기회를 마련하여 쉽게 익혀 적용할 수 있도록 하는 것이 목적이다.

<br>

# 일정

## 9월 2일 (토)
- 09:00 – 09:10 등록
- 09:15 – 09:30 인사말과 참석자, 강사 소개
- 09:30 - 10:50 : ChatGPT 소개, OpenAI API 소개
- 11:00 - 11:55 : 실습을 위한 환경 준비 [실습위한_환경_준비.pdf](실습위한_환경_준비.pdf)
- 13:00 – 13:50 : OpenAI API 실습 #1
    - API 단순 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)
- 14:00 – 14:50 : OpenAI API 실습 #2
    - API 역활 설정과 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)
    - https://platform.openai.com/examples
- 15:00 ~ 15:50 : OpenAI API 실습 #3
    - 챗봇 : [practice/tiny_chatbot.ipynb](practice/tiny_chatbot.ipynb)
- 16:00 ~ 16:50
    - 챗봇 : [practice/tiny_chatbot.ipynb](practice/tiny_chatbot.ipynb)


## 9월 3일 (일)

- 09:00 – 09:50 : 작업1. 지식인 의학 QnA의 전공과 예측 #1
    - GPT 추가 학습 : [practice/how_to_fine_tuning.ipynb](practice/how_to_fine_tuning.ipynb)
- 10:00 – 10:50 : 작업1. 지식인 의학 QnA의 전공과 예측 #2
    - 지식인 데이터 크로울링 : [practice/task1_medical_speciality.ipynb](practice/task1_medical_speciality.ipynb)
- 11:00 - 11:50 : 작업1. 지식인 의학 QnA의 전공과 예측 #3
    - GPT 추가 학습 : [practice/task1_medical_speciality.ipynb](practice/task1_medical_speciality.ipynb)
- 13:00 – 13:50 : 작업2. 의학 논문에 기반한 QnA 엔진 #1
    - 임베딩 방법 [practice/how_to_embedding.ipynb](practice/how_to_embedding.ipynb)
    - 임베딩을 사용한 분류 [practice/classification_using_embedding.ipynb](practice/classification_using_embedding.ipynb)
    - 임베딩을 사용한 추천 [practice/recommendation_using_embedding.ipynb](practice/recommendation_using_embedding.ipynb)
- 14:00 – 14:50 : 작업2. 의학 논문에 기반한 QnA 엔진 #2
    - 논문 임베딩 : [practice/task2_customer_qna_engine.ipynb](practice/task2_customer_qna_engine.ipynb)
- 15:00 - 15:50 : 작업2. 의학 논문에 기반한 QnA 엔진 #3
    - QnA 구현 : [practice/task2_customer_qna_engine.ipynb](practice/task2_customer_qna_engine.ipynb)
- 16:00 – 17:00 : 전체 과정에 대한 질문과 대답, 회고

<br>

# 워크샾 자료

- [ChatGPT_소개.pdf](ChatGPT_소개.pdf)
- GPT 구조 : [from_DNN_to_GPT.pptx](from_DNN_to_GPT.pptx)
- 실습 준비 : [실습위한_환경_준비.pdf](실습위한_환경_준비.pdf)
- [OpenAI_API_사용_기초.pdf](OpenAI_API_사용_기초.pdf)


<br>

# 참고 자료

- OpenAI 홈 : https://openai.com/
- ChatGpt 홈 : https://chat.openai.com/
- OpenAI Platform 홈 : https://platform.openai.com/
    - API 레퍼런스 : https://platform.openai.com/docs/api-reference
    - 웹에서 설명한 사용 예제 : https://platform.openai.com/examples
- OpenAI API CookBook : https://github.com/openai/openai-cookbook
