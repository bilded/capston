## 프론트엔드 관련 코드 경로 workspace/frontend/src 
## 백엔드 관련 코드 경로 workspace/backend


# 빅데이터 기반 공모전 추천 웹사이트

이 프로젝트는 빅데이터 기반 공모전 추천 웹사이트로, **프론트엔드**와 **백엔드**가 분리되어 있습니다. 데이터베이스 설계와 와이어프레임은 Notion에 정리된 내용을 참고하실 수 있습니다.

## 프로젝트 설명

이 프로젝트는 캡스톤디자인 수업의 과제물로, 백석대학교 학생들의 역량 강화를 목표로 개발되었습니다 **프론트엔드**와 **백엔드**는 서로 독립적으로 동작하며, 데이터베이스를 통해 연동됩니다.

## 파일 구조

### 백엔드 (backend)

백엔드는 Flask와 같은 웹 프레임워크를 사용하여 API를 제공합니다. 이 API는 프론트엔드와 통신하며, 데이터를 처리하고 클라이언트 요청에 대한 응답을 반환합니다.

- 백엔드의 주요 기능:
  - 사용자 인증 (JWT 사용)
  - 데이터 처리 및 저장 (MongoDB Atlas 연동)
  - API 서버 구성
  - 추천 알고리즘 (컨텐츠 기반 필터링)

### 프론트엔드 (frontend)

프론트엔드는 React.js를 사용하여 동적인 사용자 인터페이스(UI)를 제공합니다. 백엔드 API와 연동하여 데이터를 시각적으로 표시하고 사용자와의 상호작용을 처리합니다.

- 프론트엔드의 주요 기능:
  - 사용자 인터페이스(UI) 구현
  - 백엔드와의 데이터 통신 (HTTP 요청)
  - 동적인 페이지 렌더링


