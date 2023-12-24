# LANGCHAIN 웹 사이트 문서 요약 AI오픈소스 201911977_이세훈😿

허깅페이스 llm모델을 이용하여 웹 사이트 문서 요약을 하는 실습을 진행했습니다.

from langchain.chains.summarize import load_summarize_chain
요약하는 chain을 이용하여 웹 사이트 문서 요약을 진행했습니다.

https://python.langchain.com/docs/modules/chains/document/stuff
chain_type은 위의 사이트를 참고하여 stuff로 진행해 문서 목록을 가져와서 모두 프롬프트에 삽입하고 해당 프롬프트를 LLM에 전달하게 했습니다.

사용한 모델은 "mistralai/Mistral-7B-Instruct-v0.1" 아래 허깅페이스 사이트에 올라온 모델을 이용했습니다.(한국어도 가능)
https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1


# 결과 사진
![분할 성공 사진1 ](open_langchain/assets/1.png)

## 실행 방법
1. ipynb파일을 열고 모두 실행
