# ARTENS 🎨 : 전시 공간의 지능화 플랫폼

## 📌 프로젝트 소개
지능형 전시 관리 및 방문객 경험 향상을 위한 통합 플랫폼입니다. AI 기술을 활용하여 전시 공간에서 일어나는 모든 상호작용을 분석하고, 이를 통해 더 나은 전시 경험을 제공합니다.

## 🛠 기술 스택

### Backend
- <img src="https://img.shields.io/badge/JAVA-17-007396?style=flat&logo=java&logoColor=white"> 
- <img src="https://img.shields.io/badge/Spring Boot-3.2.x-6DB33F?style=flat&logo=springboot&logoColor=white">
- <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=springsecurity&logoColor=white">
- <img src="https://img.shields.io/badge/JPA-6DB33F?style=flat&logo=hibernate&logoColor=white">

### Database
- <img src="https://img.shields.io/badge/MySQL-8.0-4479A1?style=flat&logo=mysql&logoColor=white">
- <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white">

### Infrastructure
- <img src="https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white">
- <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
- <img src="https://img.shields.io/badge/GitHub Actions-2088FF?style=flat&logo=githubactions&logoColor=white">

## 🗂 프로젝트 구조
```
com.hongik.artens
├── global/
│   ├── config/          # 전역 설정
│   ├── security/        # 보안 설정
│   ├── error/           # 예외 처리
│   └── util/           # 유틸리티
├── domain/             # 도메인별 패키지
│   ├── exhibition/     # 전시 관련
│   ├── visitor/        # 방문객 관련
│   └── analytics/      # 분석 관련
└── infrastructure/     # 외부 인프라 연동
```

## 🌿 브랜치 전략
```
main
└── develop
    └── feature/기능명
    └── fix/버그수정
```

## ✏️ 커밋 메시지 컨벤션
```
[type]: 제목
```

### Type
- `feat`: 새로운 기능 추가
- `fix`: 버그 수정
- `refactor`: 코드 리팩토링
- `style`: 코드 포맷팅
- `test`: 테스트 코드
- `docs`: 문서 수정
- `chore`: 빌드, 패키지 매니저 설정

## 🔍 PR 규칙
```markdown
## 💫 관련 이슈
- close #이슈번호

## 📝 작업 내용
- 변경사항 상세 설명
- 영향을 받는 기능
- 특이사항

## ✅ 테스트 체크리스트
- [ ] 단위 테스트
- [ ] 통합 테스트
- [ ] API 테스트

## 📌 참고사항
- 구현 시 고려사항
- 논의가 필요한 사항
```

## 📋 코드 컨벤션

### 네이밍

#### Class
```java
// Controller
xxxController (예: ExhibitionController)

// Service
xxxService, xxxServiceImpl

// Repository
xxxRepository

// DTO
xxxRequestDto, xxxResponseDto (예: ExhibitionRequestDto)

// Entity
단수명사 (예: Exhibition)
```

#### Method
```java
// 조회
findXxx(), getXxx(), selectXxx()

// 생성
createXxx(), saveXxx(), insertXxx()

// 수정
updateXxx(), modifyXxx()

// 삭제
deleteXxx(), removeXxx()

// Boolean
isXxx(), hasXxx(), canXxx()
```

#### Variable
- 카멜케이스 사용
- 복수형: List는 xxxList, Map은 xxxMap
- Boolean: isXxx, hasXxx, canXxx
- 상수: 대문자 + 언더스코어 (MAX_SIZE)

## 📚 API 문서
- Swagger UI: `http://localhost:8080/swagger-ui.html`
- API 문서: `http://localhost:8080/docs`

## 👥 팀원
- Frontend: 곽은채 [https://github.com/kwaktato]
- Backend: 김다연 [https://github.com/danhandev]
- AI Vision Engineer: 박준서 [https://github.com/Pjunn]

## 📝 라이선스
This project is licensed under the MIT License

---
© 2025 ARTENS Team. All rights reserved.
