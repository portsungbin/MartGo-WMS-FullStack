# MartGo-WMS-FullStack

MartGo-WMS-FullStack는 창고 관리(Warehouse Management System)를 위한 웹 기반 애플리케이션입니다.  
Spring Framework와 MyBatis를 백엔드에, JSP를 프론트엔드로 사용하였으며, MySQL과 연동하여 데이터베이스 관리를 수행합니다.

## 🛠️ 기술 스택

### Backend
- Java 11
- Spring Framework (Spring MVC)
- MyBatis
- JDBC
- Gradle
- Lombok

### Frontend
- JSP / JSTL
- HTML5 / CSS3 / Bootstrap
- JavaScript (필요시)

### Database
- MySQL 8.x
- ERD 기반 테이블 구성 및 외래키 제약조건 적용

### Infra
- Tomcat 9
- GitHub / Git
- 네이버 클라우드 (배포 서버)

---

## 🧾 주요 기능

### 공통
- 로그인 / 로그아웃 기능
- 권한 기반 홈/마이페이지 라우팅 처리 (세션 관리)
- 비회원용 인트로 페이지

### 관리자 (총관리자 / 창고관리자)
- 사용자 관리 (회원, 거래처, 관리자 권한 부여/삭제)
- 창고 등록 및 관리 (위치, 용량 등)
- 섹터(구역) 등록 및 용량 자동 배분
- 재고 관리 및 조회
- 대시보드: 창고/섹터 상태 시각화 (진행중, 완료 등)

### 일반 사용자 (회원 / 거래처)
- 마이페이지 (정보 조회 및 수정)
- 창고 대여 요청 / 진행 상태 확인
- 상품 재고 확인
- 요청 내역 및 히스토리 열람
