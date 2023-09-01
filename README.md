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
    - API 호출 방법 : [practice/api_call_basic.ipynb](practice/api_call_basic.ipynb)
- 14:00 – 14:50 : OpenAI API 실습 #2
    - 임베딩 방법 : [practice/how_to_embedding.ipynb](practice/how_to_embedding.ipynb)
    - 학습 방법 : [practice/how_to_fine_tunning.ipynb](practice/how_to_fine_tunning.ipynb)
- 15:00 - 15:50 : 데이터 크로울링 #1 [TODO]()
- 16:00 – 17:00 : 데이터 크로울링 #2 [TODO]()

## 9월 3일 (일)
작업 1. 데이터 크로울링과 학습<br>
작업 2. 개인 문서에 대한 QnA 엔진 구축

- 09:00 – 09:50 : 작업1 - 수집된 데이터에 대한 전처리
- 10:00 – 10:50 : 작업1 - OpenAI API를 사용한 학습
- 11:00 - 11:50 : 작업1 - 질문 호출과 응답 처리
- 13:00 – 13:50 : 작업2 - 수집된 데이터에 대한 전처리
- 14:00 – 14:50 : 작업2 - OpenAI API로 데이터의 임베딩
- 15:00 - 15:50 : 작업2 - 질문의 임베딩과 답변 처리
- 16:00 – 17:00 : 전체 과정에 대한 질문과 대답, 회고

<br>

# 워크샾 자료

- [ChatGPT_소개.pdf](ChatGPT_소개.pdf)
- GPT 구조 : [from_DNN_to_GPT.pptx](from_DNN_to_GPT.pptx)
- 실습 준비 : [OpenAI_계정만들기_키만들기_결제정보_입력.pdf](OpenAI_계정만들기_키만들기_결제정보_입력.pdf)
- [OpenAI_API_사용_기초.pdf](OpenAI_API_사용_기초.pdf)


<br>

# 참고 자료

- OpenAI 홈 : https://openai.com/
- ChatGpt 홈 : https://chat.openai.com/
- OpenAI Platform 홈 : https://platform.openai.com/
    - API 레퍼런스 : https://platform.openai.com/docs/api-reference
    - 웹에서 설명한 사용 예제 : https://platform.openai.com/examples
- OpenAI API CookBook : https://github.com/openai/openai-cookbook