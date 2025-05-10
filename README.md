# Node_API_Server

이 프로젝트는 물류 공급 관리 시스템의 백엔드 서버로, React Native 앱에서 사용하는 공급일자, 배송유형, 센터/코스 정보 등을 REST API 형태로 제공합니다.
현재 공개된 코드는 민감한 설정 정보(DB 연결, 인증 키 등)를 제거한 상태이며, 구조 및 엔드포인트 흐름을 공유하는 용도로 작성되었습니다.

---

## 주요 기능

- API 조회
- - JWT 기반 인증 처리 (일부 삭제)
- 로그 기록 및 요청 처리 흐름 관리

---

## 사용 기술

- Node.js + Express
- TypeScript
- CORS, Helmet 등 보안 미들웨어
- Oracle (DB 설정은 사용 환경에 따라 분기)

---

## 실행 방법

1. 저장소 클론

```bash
git clone https://github.com/kth9107/ReactNative_App.git
cd Node_API_Server
