# 🎲 보드게임 챗봇

> AI 기반 보드게임 도우미 플랫폼

## 🚀 무엇을 만드나요?

**보드게임 챗봇**은 보드게임 플레이어들을 위한 지능형 어시스턴트입니다:

- 📖 **룰 설명** - 게임 규칙에 대한 즉시 답변 제공
- 🎯 **게임 추천** - 취향에 맞는 완벽한 게임 찾기  
- 🤖 **AI 기반 응답** - 200개 이상의 보드게임 룰로 훈련된 스마트 챗봇
- 📱 **웹 인터페이스** - 사용하기 쉬운 Django 웹 애플리케이션

## 🏗️ 아키텍처

플랫폼은 3개의 주요 구성요소로 이루어져 있습니다:

| 레포지토리 | 설명 | 기술 스택 |
|------------|------|-----------|
| [**Backend**](https://github.com/boardgame-chatbot-bovi/boardgame-chatbot-backend) | RAG 시스템을 갖춘 AI 추론 서버 | Python, FastAPI, FAISS, RunPod |
| [**Frontend**](https://github.com/boardgame-chatbot-bovi/boardgame-chatbot-frontend) | 웹 애플리케이션 인터페이스 | Django, HTML/CSS/JS |
| [**Docs**](https://github.com/boardgame-chatbot-bovi/boardgame-chatbot-docs) | 문서 및 자료 | Markdown, Images |

## 🎮 주요 기능

- **200개 이상 보드게임** 상세한 룰 설명 지원
- **한국어 최적화** 한국 보드게임 커뮤니티를 위한 최적화
- **RAG 시스템** FAISS를 사용한 정확한 룰 검색
- **모바일 친화적** 반응형 웹 디자인
- **실시간 채팅** 인터랙티브 대화 인터페이스

## 🛠️ 기술 스택

**백엔드:**
- Python 3.12+
- FastAPI
- FAISS (벡터 데이터베이스)
- OpenAI API
- RunPod (GPU 클라우드)

**프론트엔드:**
- Django 4.2+
- HTML/CSS/JavaScript
- SQLite 데이터베이스

**배포:**
- Docker
- AWS EC2
- Nginx

## 📊 게임 데이터베이스

챗봇은 다음과 같은 인기 보드게임 룰로 훈련되었습니다:

🎯 **전략 게임:** 카탄, 스플렌더, 아줄, 윙스팬  
🃏 **카드 게임:** 우노, 러브레터, 쿠, 시타델  
🎲 **파티 게임:** 코드네임, 딕싯, 텔레스트레이션  
🧩 **가족 게임:** 티켓 투 라이드, 블로커스, 시퀀스  

## 🤝 기여하기

보드게임 커뮤니티의 기여를 환영합니다! 

- 🐛 이슈를 통한 버그 리포트 및 기능 제안
- 📝 문서 개선 
- 🎮 새로운 보드게임 룰 데이터베이스 추가
- 🔧 코드 개선 기여

## 👥 팀

SKN 11기 3팀이 ❤️로 만들었습니다

---

*🎲 AI를 통해 보드게임을 더욱 접근하기 쉽게*