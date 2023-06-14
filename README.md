# 스프링 AOP
## 스프링 AOP 구현
+ v1 - 시작
+ v2 - 포인트컷 분리
+ v3 - 어드바이스 추가
+ v4 - 포인트컷 참조
+ v5 - 어드바이스 순서
+ v6 - 어드바이스 종류

## 포인트컷
+ execution1
+ execution2
+ within
+ args
+ @target, @within
+ @annotation, @args
+ bean
+ 매개변수 전달
+ this, target

## 실전 예제
+ 로그 출력 AOP
+ 재시도 AOP

## 실무 주의사항
+ 프록시와 내부 호출
  + 대안1 자기 자신 주입
  + 대안2 지연조회
  + 대안3 구조 변경
+ 프록시 기술과 한계
  + 타입 캐스팅
  + 의존관계 주입
  + CGLIB
  + 스프링의 해결책
