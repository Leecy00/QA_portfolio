<img width="1256" height="243" alt="image" src="https://github.com/user-attachments/assets/4db25fac-b3fb-4ab2-8913-e8403d9d53c1" /># QA 포트폴리오

## 소개
QA 직무 취업 준비 포트폴리오입니다.
Jira를 활용한 버그 트래킹 및 테스트 케이스 관리 실습을 기록합니다.

## 사용 툴
- Jira Software (버그 트래킹 / 스프린트 관리)
- Selenium + JUnit (테스트 자동화) - 예정

## 버그 리포트 실습 (Saucedemo.com)

### SCRUM-7 | 가격 낮은순 정렬 시 상품 순서가 올바르지 않음
- **재현 단계**: 상품 목록 → 정렬 드롭다운 → Price (low to high) 선택
- **기대 결과**: 가격 오름차순으로 상품 정렬
- **실제 결과**: 일부 상품 순서가 가격 오름차순과 다르게 표시
- **우선순위**: Medium

### SCRUM-8 | About 메뉴 클릭 시 외부 사이트로 이동됨
- **재현 단계**: 햄버거 메뉴 클릭 → About 선택
- **기대 결과**: 앱 내 About 페이지로 이동
- **실제 결과**: saucelabs.com 외부 사이트로 이동
- **우선순위**: Medium

## 진행 현황
- [x] Jira 환경 세팅
- [x] Bug 이슈 생성 및 스프린트 관리
- [x] 실제 사이트 버그 발견 및 리포트 작성
- [x] 테스트 케이스 작성 (등가분할 / 경계값 분석)
- [x] Selenium 자동화 테스트
