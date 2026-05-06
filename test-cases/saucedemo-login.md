# 테스트 케이스 - Saucedemo 로그인

## 테스트 대상
- 사이트: saucedemo.com
- 기능: 로그인

## 테스트 케이스 목록

| TC-ID | 테스트 항목 | 입력값 | 기대 결과 | 실제 결과 | 결과 |
|---|---|---|---|---|---|
| TC-001 | 정상 로그인 | ID: standard_user / PW: secret_sauce | 메인 상품 페이지 이동 | 메인 상품 페이지 이동 | PASS |
| TC-002 | 잘못된 비밀번호 | ID: standard_user / PW: 1234 | 오류 메시지 표시 | 오류 메시지 표시 | PASS |
| TC-003 | ID 미입력 | ID: 없음 / PW: secret_sauce | 오류 메시지 표시 | 오류 메시지 표시 | PASS |
| TC-004 | 잠긴 계정 로그인 | ID: locked_out_user / PW: secret_sauce | 잠긴 계정 오류 메시지 | 잠긴 계정 오류 메시지 | PASS |
| TC-005 | 공백 입력 | ID: 공백 / PW: 공백 | 오류 메시지 표시 | 오류 메시지 표시 | PASS |

## 사용 기법
- 등가 분할: 유효한 값 / 유효하지 않은 값 구분
- 경계값 분석: 빈 값 / 공백 입력 케이스
