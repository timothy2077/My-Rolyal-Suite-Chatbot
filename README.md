# My-Rolyal-Suite-Chatbot

Project Popillius Roadmap

A. Phase 0: 데이터 전처리하기
1.	기초 데이터: 데이터셋의 행과 열 크기, 타임 정보, 결측값, 기초 통계량 점검
2.	결측값 및 중복 데이터: 결측값 대체 또는 제거, 중복 데이터 정리
3.	데이터 스케일링: 데이터 정규화
4.	범주형 데이터 인코딩: 범주형 데이터를 수치형 데이터로 변환
5.	텍스트 분류기 준비: 텍스트 데이터 분류 준비

B. Phase 1: 자연어 처리하기
1.	spaCy: spaCy 모델 활용
2.	NLP 처리: 형태소 분석, 어간 추출, 표제어 추출, 개체명 인식, 불용어 처리, 의존 구문 분석, 명사 덩어리 추출, 유사도 확인
3.	토큰화 및 정규 표현식: 텍스트 토큰화, 정규 표현식 사용

C. Phase 2: Dialogflow 챗봇 구현하기
1.	룸서비스 챗봇 개발: 인텐트 생성, 어터런스 추가, 기본 응답과 품목 명세 인텐트 및 엔티티 생성
2.	Dialogflow 챗봇: 웹 배포

D. Phase 3: Rasa NLU 챗봇 구현하기
1.	모델 훈련 및 학습: Rasa NLU 모델 훈련
2.	모델 예측: 모델 예측 수행
3.	대화 관리 시스템 구축: 도메인 파일 생성, 대화 관리 시스템 구축
4.	Custom Actions 정의: 사용자 정의 액션 정의
5.	스토리 데이터 생성
6.	대화형 학습
7.	스토리로 대화 추출
8.	Rasa 챗봇 테스트
9.	텔레그램 챗봇 구현

E. Phase 4: Gemma LLM 챗봇 구현하기
1.	Transformers Library Import: Transformers 라이브러리 가져오기
2.	Telegram Bot 토큰 설정
3.	데이터셋 로드
4.	Hugging Face Gemma 모델 및 토크나이저 로드
5.	답변 생성 함수 정의
6.	명령어 처리기 정의
7.	사용자 메시지 처리
8.	모델 Fine-tuning 및 훈련
9.	메시지 수신 대기
10.	텔레그램 챗봇 구현

F. Phase 5: ChatGPT 챗봇 구현하기
1.	API Key 발급: OpenAI API 키 발급
2.	텔레그램 챗봇 구현 A: 텔레그램 실시간 통신 구현 
3.	텔레그램 챗봇 구현 B: FastAPI 및 ngrok 서버 생성, 텔레그램 서버 연결
4.	아마존 웹 서비스 텔레그램 챗봇 구현: AWS 텔레그램 챗봇 구현
5.	카카오톡 챗봇 구현 A: FastAPI 및 ngrok 서버 생성, 카카오톡 서버 연결
6.	카카오톡 챗봇 구현 B: AWS 카카오톡 챗봇 구현

G. Phase 6: 스트림릿으로 챗봇 구현하기
1.	ChatGPT를 이용한 데이터 전처리
2.	OpenAI의 Embedding API와 코사인 유사도 검색 시스템 구현
3.	스트림릿 앱 구현

H. Phase 7: 랭체인으로 RAG 기반의 챗봇 구현하기 (Model A)
1.	아나콘다 설치
2.	가상 환경 생성
3.	랭체인 및 필요한 라이브러리 설치
4.	OpenAI와 Hugging Face API 키 발급
5.	Dataset Load 및 OpenAI Tools를 통한 데이터 전처리
6.	모델 I/O, 데이터 연결, 체인, 메모리, 에이전트 및 툴 점검
7.	텔레그램 챗봇 구현

I. Phase 8: Gradio로 챗봇의 UI 만들기 
1.	Gradio 라이브러리 설치
2.	Phase 7의 챗봇 웹 배포

J. Phase 9: 랭체인으로 RAG 기반의 챗봇 구현하기 (Model B)
1. 환경 설정: Langchain 설치
2. 데이터 전처리: 데이터셋 준비, 임베딩 생성
3. FAISS 벡터 저장소 설정: FAISS 사옹
4. RAG 파이프라인 구축: RAG & Retrieval Chain 구현, 구문 요약
5. 다양한 LLM 실험: 대형 언어 모델 실험, 최적의 모델 선택
6. 사용자 인터페이스 구축: Gradio를 사용한 Chat UI 구현, Test & Feedback

K. Phase 10: Firebase & GCP에서 Gemini API로 챗봇 구축 
1.	Firebase와 GCP Project 설정, API 키 생성 
2.	Firebase 인증 및 Firestore 설정
3.	Gemini API 활성화
4.	Firebase Functions 서버리스 환경 구축
5.	Gemini API 요청 구성
6.	답변 생성 로직 작성
7.	오류 처리 및 예외 처리
8.	Firebase CLI 설치 및 프로젝트 연동
9.	챗봇 엔드포인트 작성
10.	챗봇 로직을 Firebase Functions에 배포
11.	Firestore 데이터 베이스와 연동
12.	Flutter를 이용한 UI 개발 
13.	Firebase SDK 통합
14.	Fiebase 호스팅
15.	Firebase Console을 통해 모니터링
16.	유지관리 및 고도화 (확장 프로그램 설치)
17.	확장 프로그램 Customization
(gemini-1.5-pro선택, Firestore 컬렉션 경로 입력, 메시지 문서 생성, 대화 기록 수집, 언어 모델 쿼리, 응답 작성, 컨텍스트 및 매개변수 구성, 챗봇 역할 설정 등)

L. Phase 11: Gemma LLM Fine-Tuning 모델 챗봇 구현하기
1. Transformer Library Import
2. Telegram Bot 토큰 설정
3. 데이터셋 로드 
4. HuggingFace Gemma 모델 및 토크나이저 Import
5. 답변 생성 함수 및 명령어 정의
6. 사용자 메시지 처리
7. 모델 Fine-Tuning 및 훈련
8. 메시지 수신 대기 
9. 텔레그램 챗봇 구현

M. Phase 12: 발표자료 만들기 







