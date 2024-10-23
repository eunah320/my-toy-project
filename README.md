# Pair Programming: Instagram Clone Project
Django, React, PostgreSQL을 이용한 인스타그램 페어 클론 코딩

## 프로젝트 개요

이 프로젝트는 Django와 React를 기반으로 한 웹 애플리케이션 개발을 목표로 합니다. Django 프레임워크를 활용하여 차후 진행될 장고 관통 프로젝트에서 요구되는 기술적 능력을 사전에 습득하고, 프론트엔드 기술, Git 활용 능력, 문서화 및 프로젝트 관리 역량을 구체화할 증거 자료를 마련하고자 합니다.

## 프로젝트 성격

이 프로젝트는 개인 프로젝트 성향을 지닌 페어 프로젝트입니다. 각자는 프로젝트 내 모든 기능을 직접 구현하고 설명할 수 있는 능력을 갖추기 위해, 서로의 기능을 교환하여 작업하고 충돌 상황을 해결하는 경험을 쌓습니다.

### 팀 프로젝트 운영 방식

- 각자 개별 레포지토리를 생성하고, 상대방을 컨트리뷰터로 추가하여 작업을 진행합니다.
- 기능별로 브랜치를 분리하여 개발하며, 주기적으로 코드 리뷰 및 피드백을 진행합니다.

## 목표

1. Django 프레임워크를 활용한 백엔드 로직 이해 및 기능 구현
   - Django를 사용한 RESTful API 개발 능력 습득
   - WebSocket과 Django Channels를 활용한 실시간 데이터 처리 기능 구현
2. React, PostgreSQL 연동 및 관련 기술 역량 강화
   - React와 Django 간 연동 및 프론트엔드-백엔드 통신 구조 학습
   - PostgreSQL 데이터베이스와의 연동 및 데이터 관리 능력 향상
3. 협업 및 프로젝트 관리 역량 강화
   - Git Workflow 및 Git Flow를 활용한 브랜치 관리
   - 문제 및 해결 방법 문서화 및 공유

## 기술 스택

- **백엔드 프레임워크**: Django
- **프론트엔드 라이브러리**: React
- **데이터베이스**: PostgreSQL
- **실시간 통신**: WebSocket, Django Channels
- **배포**: AWS 또는 Heroku (추후 결정)

## 미팅 및 커뮤니케이션

- **정기 미팅**: 매주 수요일 점심 시간 (필요시 목요일 추가 미팅)
- 진행 상황 공유 및 다음 작업 계획 수립

## 작업 프로세스

1. **미팅**: 진행 상황 공유 및 학습 내용 토의
2. **작업 준비**: 강의를 참고하여 학습 및 작업 계획 수립
3. **PR 작성 및 리뷰**: 작업 후 PR 작성, 피드백 제공
4. **문서화**: 작업 내용 회고 및 공유

## 구현할 기능

### 필수 기능
- 사용자 인증 및 프로필 관리
- 게시물 작성, 좋아요, 댓글 기능
- 피드 기능
- 팔로우 및 팔로워 관리
- 사용자 및 게시물 검색 기능

### 선택 기능
- 스토리 기능
- 소셜 로그인 기능
- DM (Direct Messaging) 기능
- 알림 기능
- 해시태그 및 위치 태그 기능

## 주차별 계획

### 1주차: 백엔드 기본 세팅 및 PostgreSQL 학습
 - 장고 구현 연습
 - branch 네이밍 규칙 공부하기 & branch 분리해서 기능 단위로 작업
 - commit convention 공부하기 & commit message 최소 작업 단위로 잘 찍기
 - Channels 강의 보기
### 2주차: 사용자 인증 및 필수 기능 구현
### 3주차: 선택 기능 구현 및 React-백엔드 연결 학습
### 4주차: 추가 선택 기능 구현 및 서버 간 연결 작업
### 5주차: 프론트엔드 작업 및 배포 준비
### 6주차: 최종 작업 마무리 및 문서화

## 참고 강의 및 영상

- [강의 1](https://www.youtube.com/watch?v=EOpI1y59aNU&list=PLi4xPOplIq7duIjdi94TucOyYG-s3fA7J&index=2)
- [강의 2](https://www.youtube.com/watch?v=M8UPyeF5DfM&list=PLHQvFs5CMVoQd-N0MeIOfexq91Tuyv1vZ&index=1)
- [참고 자료 1](https://gmlwjd9405.github.io/2018/05/11/types-of-git-branch.html)