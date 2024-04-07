# 도배 하자 질의 응답 처리 : 한솔데코 시즌2 AI 경진대회

## 대회 소개
- 주제 : 도배 하자 질의응답 AI 모델 개발
- 대회 기간 : 2024년 01월 29일 ~ 2024년 03월 14일
- 주최/주관
  - 주최 : 한솔데코
  - 주관 : 데이콘


## 결과
> **Private 27th(상위 5% 이내)**
> 
> ![image](https://github.com/baesooyeon/llm-qa-dacon-2024/assets/102578702/ebe7abae-6824-4114-8615-e43b26fcb144)



## 상세내용
[pdf](https://github.com/baesooyeon/llm-qa-dacon-2024/blob/main/2.pdf/%EB%8F%84%EB%B0%B0%ED%95%98%EC%9E%90_ppt_%EB%8F%84%EB%B0%B0%EB%8B%A8.pdf) 및 [code](https://github.com/baesooyeon/llm-qa-dacon-2024/tree/main/1.code) 참고


## Files
- `loader.py`
  : 데이터셋, 모델 그리고 토크나이저 등을 불러오는 모듈
- `run_sft.py`
  : sft 실행 모듈
- `rag.py`
  : 질문과 유사도가 높은 문서 추출 모듈
- `utils.py`
  : prompt template 설정 모듈
- `run.sh`
  : sft 실행 shell 파일
- `run_rag.sh`
  : rag를 이용한 sft 실행 shell 파일
- `model/final_`
  : 학습된 모델


