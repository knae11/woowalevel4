# 2021 우아한테크코스 레벨4
Http 서버 구현, MVC 프레임워크 구현, JDBC Template 구현

## 미션 목록
- 코드로 구현하며 추상화 된 동작방식을 이해
- [리팩터링](https://github.com/knae11/woowalevel4/tree/refactoring)
    - 기존 레거시 코드의 도메인을 파악하고 리팩터링을 위한 테스트 코드를 작성
    - JdbcTemplate, Dao, Domain으로 이루어진 코드를 JPA, DTO를 사용하여 리팩터링
    - 패키지간, 클래스간 단방향 의존관계 설정
    - 멀티모듈로 패키지 분리
- [jdcb](https://github.com/knae11/woowalevel4/tree/jdbc)
    - 기본 DAO에서 find, insert 구현이 된 코드를 리팩토링하며 추가 기능 구현
    - 익명 클래스, 함수형 인터페이스, 람다
    - 제네릭
    - 가변 인자
    - 템플릿 콜백 패턴
    - try-with-resources
    - checked vs unchecked exception
- [mvc 프레임워크](https://github.com/knae11/woowalevel4/tree/mvc)
    -  기존 ManualController로 되어있는 내용을 AnnotationController로 변환하는 작업 
    -  Java Reflection
    -  [Spring Web MVC DispatcherServlet](https://nauni.tistory.com/300)
- [http 서버](https://github.com/knae11/woowalevel4/tree/http)
    - http 요청을 읽고 해석하여 적절한 응답을 반환하는 기능 구현
    - [reflection을 사용하여 GetMapping annotation 만들기](https://nauni.tistory.com/293)
    - [File, inputStream, outputStream](https://nauni.tistory.com/294)
    - [http/1.1 프로토콜](https://nauni.tistory.com/295) 
## 학습내용 블로그 정리
[우테코 레벨4 과정](https://nauni.tistory.com/category/%EC%9A%B0%EC%95%84%ED%95%9C%ED%85%8C%ED%81%AC%EC%BD%94%EC%8A%A4/%EB%A0%88%EB%B2%A84)
