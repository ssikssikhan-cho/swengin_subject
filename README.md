#소프트웨어공학 과제2: 공유 자전거 대여 시스템

본 프로젝트는 사용자(회원, 관리자)가 참여하는 **공유 자전거 대여 시스템**을 설계하고, 요구사항 명세에 기반한 객체지향적인 분석과 구현을 수행한 결과물입니다.

---

## 기능 요약

### 회원 기능
- 회원가입
- 로그인 / 로그아웃
- 자전거 대여
- 대여 정보 조회
- 시스템 종료

### 관리자 기능
- 로그인 / 로그아웃
- 자전거 등록
- 시스템 종료

---

## 시스템 설계 요약

### 1. Requirement List
- 회원은 자전거를 대여할 수 있다.
- 관리자는 자전거를 등록할 수 있다.
- 로그인/로그아웃 후 상태 유지 및 종료 시 전체 초기화된다.

### 2. Analysis Class Diagram
- 주요 클래스: `User`, `Admin`, `Bike`, `BikeRegistrar`, `BikeRentalController`, `RentalInfoController`, `LoginController`, `SystemController`
- UI 클래스: `UserUI`, `AdminUI`, `LoginUI`
- 각 클래스 간 연관 관계, 책임, 다중도 및 역할 명확히 명시

### 3. Use Case Description
각 기능마다 사용자의 동작과 시스템의 반응을 단계별로 기술하였고, 일반 흐름과 예외 흐름을 포함한 기술이 완료되었습니다.

### 4. Communication Diagram
기능별 객체 간 메시지 흐름을 시각화하여 다음 내용을 포함함:
- `RegisterUser`
- `LoginUser`
- `RegisterBike`
- `RentBike`
- `ViewRentalInfo`
- `LogoutUser`
- `ExitSystem`

## 개발 환경

- **언어:** C++
- **도구:** StarUML, MS Word / 한글
- **버전관리:** Git


