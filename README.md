# commento
코멘토 백엔드 실무 과정 1주차


1. Maria DB를 사용하여 데이터 베이스와 테이블 생성.


    ~ 이슈 1. 3306 포트가 이미 사용 중을 알리는 에러 발생.


              -> Maria DB는 기본적으로 호환성과 편의성을 위해 SQL과 같은 포트 번호를 기본값으로 사용.


                 SQL을 삭제하고 Maria DB에게 3306 포트를 배정해줌으로서 해결.

 
3. Spring MVC 환경설정 및 API Ping


   ~ JDK 11 -> Azul 사용.


   ~ IntelliJ Community에서는 톰캣이 제공되지 않음에 따라 Jetty를 사용하여 설정 진행.


5. datasource & mybatis 연동


   ~ statistic DB의 request_info 테이블에 샘플 데이터를 INSERT하고 localhost 환경에서 성공적으로 출력됨을 확인.
