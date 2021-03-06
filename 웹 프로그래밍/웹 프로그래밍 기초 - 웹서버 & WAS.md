## 웹 서버란?
* 보통 소프트웨어를 칭하지만, 웹 서버 소프트웨어가 동작하는 컴퓨터를 말함
* 웹 서버의 가장 중요한 기능은 클라이언트(Client)가 요청하는 HTML 문서나 각종 리소스(Resource)를 전달하는 것
* 웹 브라우저나 웹 크롤러가 요청하는 리소스는 컴퓨터에 저장된 정적(static)인 데이터이거나 동적인 결과가 될 수 있음

## WAS란?
* 일종의 미들웨어로, 웹 클라이언트의 요청 중 웹 애플리케이션이 동작하도록 지원하는 목적을 가짐
* 미들웨어: 클라리언트 쪽에 비즈니스 로직이 많은 경우, 관리로 인해 비용이 많이 발생하는 문제점을 해결하기 위해 클라이언트와 DBMS 사이의 미들웨어 서버에서 동작하도록 함으로써 클라이언트는 입출력만 담당하도록 함

### 웹 서버 VS WAS
* WAS도 보통 자체적으로 웹 서버 기능을 내장하고 있음
* 규모가 커질수록 웹 서버와 WAS를 분리함
* 자원 이용의 효율성 및 장애 극복, 배포 및 유지보수의 편의성을 위해 웹 서버와 WAS를 보통 분리
