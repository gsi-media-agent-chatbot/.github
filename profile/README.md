# GSI Media Agent ChatBot

🎯 멀티 모듈 기반의 AI 챗봇 프로젝트

## 🔧 구성 레포지토리
- [gsi-agent-backend](https://github.com/gsi-media-agent-chatbot/gsi-agent-backend)
  Kotlin + Spring Boot 기반 API 서버  
  ✅ **Version**:
  - Kotlin: `1.9.25`
  - Spring Boot: `3.2.2`
  - Java: `17` (JDK Toolchain)
  - Spring Dependency Management Plugin: `1.1.7`

  🔗 전체 의존성 목록은 [`build.gradle.kts`](https://github.com/gsi-media-agent-chatbot/gsi-agent-backend/blob/main/build.gradle.kts) 참고

- [gsi-agent-frontend](https://github.com/gsi-media-agent-chatbot/gsi-agent-frontend)
  React 기반 프론트엔드  
  ✅ **Version**:
  - React: `19.0.0`
  - React DOM: `19.0.0`
  - React Router DOM: `7.4.1`
  - Vite: `6.2.0`
  - React 타입 정의: `@types/react 19.0.10`
 

- [gsi-agent-ai](https://github.com/gsi-media-agent-chatbot/gsi-agent-ai)
  Python FastAPI 기반 AI 서버
  ✅ **Version**:
  - Python: 3.11
  - FastAPI: 0.110.0
  - OpenAI SDK: 1.68.2
  - LangChain: 0.3.21
  ➡️ 자세한 버전은 [requirements.txt](https://github.com/gsi-media-agent-chatbot/gsi-agent-ai/requirements.txt) 참조
📌 개발 조직: 
