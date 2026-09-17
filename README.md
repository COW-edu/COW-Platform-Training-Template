# COW Platform Training Template

COW-edu 플랫폼팀 양성 프로젝트용 템플릿 레포입니다.
실제 업무 진행 전, 팀원들이 프론트/백엔드 협업 구조에 익숙해지도록 연습하는 용도로 사용합니다.

매 학기 이 템플릿을 기반으로 새 레포를 생성해서 진행할 예정입니다.

## 폴더 구조

```
COW-Platform-Training-Template/
├── frontend/     # React + Vite
├── backend/      # Spring Boot (Java)
└── README.md
```

## 기술 스택

- **Frontend**: React, Vite, ESLint
- **Backend**: Spring Boot, Gradle, Java 17, Lombok, Validation, Spring Data JPA
- **DB**: MySQL

## 실행 방법

### 1. 저장소 클론

```bash
git clone https://github.com/COW-edu/COW-Platform-Training-Template.git
cd COW-Platform-Training-Template
```

### 2. 백엔드 실행

IntelliJ IDEA로 `backend` 폴더를 열고, `BackendApplication.java`의 main 메서드를 실행합니다.

`http://localhost:8080` 에서 서버 확인 가능.

### 3. 프론트엔드 실행

```bash
cd frontend
npm install
npm run dev
```

`http://localhost:5173` 에서 화면 확인 가능.

## 데이터베이스

MySQL은 Docker로 로컬에 띄워 사용합니다. `docker-compose.yml`은 각 프로젝트 진행 시 팀 상황에 맞게 직접 구성합니다.

## 개발 환경

- IDE: IntelliJ IDEA (백엔드) / VS Code (프론트엔드)
- Java 17
- Node.js 최신 LTS