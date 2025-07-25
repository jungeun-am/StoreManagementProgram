# 매장관리 시스템

매장 내 주문, 결제, 메뉴 관리 등을 효율적으로 처리하기 위해 개발한 POS(Point of Sale) 시스템 소프트웨어입니다.

## 📌 프로젝트 개요

매장관리 시스템은 반복적인 매장 업무의 편의성과 속도를 높이고, 업무 부담과 시간을 절감하기 위해 개발되었습니다. Java Swing을 활용하여 사용자 친화적인 인터페이스를 제공하며, Oracle 데이터베이스를 사용하여 데이터를 안전하게 관리합니다.

## 🚀 주요 기능

- **직원 등록**
  - 새로운 직원 등록
  - 아이디 중복 확인
  - 입력 데이터 유효성 검사 (아이디 길이, 비밀번호 규칙 등)

- **메뉴 관리**
  - 카테고리별 메뉴 조회 및 선택 (버거, 세트, 음료, 사이드 등)
  - 주문 목록에 메뉴 추가 및 삭제
  - 직관적인 콤보박스 선택 기능 제공

- **주문 및 결제**
  - 주문 진행 및 실시간 테이블 반영
  - 잘못된 입력이나 중복 결제 방지
  - 결제 완료 후 초기 화면으로 이동

- **UI/UX**
  - Java Swing 기반 UI로 데스크탑 환경에서 원활하게 작동
  - 테이블 행 비활성화로 잘못된 수정 방지
  - 화면 전환을 위한 ActionListener 활용

- **데이터베이스 연동**
  - JDBC를 통해 Oracle 데이터베이스와 연동
  - 주문, 메뉴, 직원 정보 등 모든 데이터를 안전하게 관리

- **보안**
  - 암호화 및 유효성 검사로 데이터 보호

## 🛠️ 기술 스택

- **언어:** Java SE
- **UI:** Java Swing
- **데이터베이스:** Oracle
- **DB 연동:** JDBC

## 💡 향후 개선 사항

- 모바일 앱 연동으로 원격 주문/결제 기능 추가
- 디지털 서명 등 보안 기능 강화
- 판매 및 재고 분석을 위한 통계 대시보드 개발

## 🔗 Repository

[여기에 깃허브 레포지토리 링크를 입력하세요]
