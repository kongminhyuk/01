# 판례검색시스템

## 프로젝트 개요
### 제목: 판례검색프로그램
=======

#### 기능: 키워드를 입력하면 관련도 순으로 판례를 제공

#### 사례
사건번호, 키워드를 입력받아 판례 검색서비스를 지원하는 기존의 LBOX 서비스
링크: https://lbox.kr/v2

#### 실행방법
웹 API지그

#### 라이브러리 - 데이터셋
lbox_open
datasets

#### 라이브러리 - NLP
transformers
rouge_score

#### 라이브러리 - 인공지능 모델 학습
pytorch_lightning
matplotlib.pyplot

#### 라이브러리 - API 및 배포
--upgrade setuptools
openai
fastapi

#### 개발환경 및 언어
구글 colab
파이썬
torch, 

#### 참고
https://github.com/lbox-kr/lbox_open.git

## 역할분담
|역할|담당자|
|---|---|
|UI|임유림,정민서|
|데이터전처리|허정원,김지우|
|chatgpt api|정도훈|
|ML Engineering|공민혁, 허정원|

## 사용 모델
[데이터](https://blog.lbox.kr/lbox-open)
# case corpus
#data_corpus = load_dataset("lbox/lbox_open", "case_corpus")

# casename classficiation task
#data_cn = load_dataset("lbox/lbox_open", "casename_classification")

# statutes classification task
#data_st = load_dataset("lbox/lbox_open", "statute_classification")

# case summarization task
#data_summ = load_dataset("lbox/lbox_open", "summarization")


## 사용 모델
[데이터](https://blog.lbox.kr/lbox-open)
