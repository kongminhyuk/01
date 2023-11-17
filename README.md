# 판례검색시스템

## 프로젝트 개요
### 제목: 판례검색프로그램
### 소개: 판례를 챗봇의 형태로 검색할 수 있게 해주는 프로그램으로 보다 편리한 판례 및 법률 관련 정보를 검색 및확인할 수 있도록 도움을 주는 프로그램입니다.
=======

#### 기능: 판례 및 키워드를 검색하면 인공지능이 유사성을 판단하여 관련 법률 및 판례 정보를 제공

#### 사례
사건번호, 키워드를 입력받아 판례 검색서비스를 지원하는 기존의 LBOX 서비스
링크: https://lbox.kr/v2

#### 실행방법
웹 인터페이스를 통해 검색하고자 하는 사례 및 키워드를 입력
인공지능이 가장 유사한 법률 및 판례 정보를 사용자에게 제공

#### 라이브러리
## 데이터셋
datasets
!git clone https://github.com/lbox-kr/lbox_open.git

## NLP
transformers
rouge_score
sentencepiece
torch

## 인공지능 모델 학습
pytorch_lightning
MT5ForConditionalGeneration

## API 및 배포
openai
gpt-3.5-turbo

#### 개발환경 및 언어
구글 colab
파이썬

#### 사용 예제
-

#### 참고
https://github.com/lbox-kr/lbox_open.git

## 역할분담
|역할|담당자|
|---|---|
|UI|임유림,정민서|
|데이터전처리|허정원,김지우|
|chatgpt api|정도훈|
|ML Engineering|공민혁, 허정원|

## 데이터셋
[데이터](https://blog.lbox.kr/lbox-open)
# case corpus
#data_corpus = load_dataset("lbox/lbox_open", "case_corpus")

# casename classficiation task
#data_cn = load_dataset("lbox/lbox_open", "casename_classification")

# statutes classification task
#data_st = load_dataset("lbox/lbox_open", "statute_classification")

# case summarization task
#data_summ = load_dataset("lbox/lbox_open", "summarization")

