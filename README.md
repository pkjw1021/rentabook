# Team 3 - Book Rental (책 대여 서비스)
## 구현 Repository
1. 책 상품 관리: https://github.com/team34final/rentabook/tree/main/Book
2. 주문 관리:
3. 배송 관리:
4. 고객 페이지:
5. 게이트웨이:

## Table of Contents
* 서비스 시나리오
  * 시나리오 테스트 결과
* 분석/설계
* 구현
  * DDD의 적용
  * Gateway 적용
  * 폴리글랏 퍼시스턴스
  * 동기식 호출과 Fallback 처리
  * 비동기식 호출과 Eventual Consistency
* 운영
  * CI/CD 설정

## 서비스 시나리오
### 기능적 요구사항
1. 고객이 책 대여를 신청한다.
2. 주문이 접수된다.
3. 요청한 책의 배송이 시작된다.
4. 고객이 책 대여를 취소할 수 있다.
5. 대여가 취소되면 배송이 중지된다.
6. 고객이 자신의 주문 정보를 확인할 수 있다.

### 비기능적 요구사항

