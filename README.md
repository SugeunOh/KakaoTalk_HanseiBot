# KakaoTalk API - JAVA + AWS

 * 이클립스(Neon Ver.) 사용
 * AWS Dev ToolKit
 * JSON 이용
 * 카카오톡 플러스친구 API 사용
 * AWS S3, IAM Role, Lambda services

### 학교 정보를 얻을 수 있는 편의용으로 키워드형식 챗봇 개발

[카카오톡 플러스친구 REST API](https://github.com/plusfriend/auto_reply) 이용

 * 카카오톡 플러스친구 API
 * AWS Lambda
 * AWS API Gateway
 * OpenWeatherMap API로 날씨 이용 - 경도, 위도 설정

### AWS Service 이용

 * AWS Lambda Function Upload
 * Lambda 서비스로 24시간 가능하게 클라우드 이용
 * 대화 시작시로 만들었던 프로젝트는 keyboard 리소스로 이용, API Gateway에서 리소스 이름을 keyboard로 생성, 메소드는 Get타입으로 생성
 * 대화 도중시로 만들었던 프로젝트는 message 리소스로 이용, API Gateway에서 리소스 이름을 message로 생성, 메소드 타입은 POST로 생성
 * message 리소스의 메소드 생성 완료 후 API 배포, 배포된 웹 URL을 이용하여 플러스친구 스마트채팅 API에서 이용
 * message와 buttons 오브젝트 구현
 
 
 ##### *완료 모습*
 
 ![완료모습](http://img1.daumcdn.net/thumb/R1920x0/?fname=http%3A%2F%2Fcfile28.uf.tistory.com%2Fimage%2F9955083359FB3F822F0054)
 
 
 ##### *수정 된 모습*
 
 ![수정](https://i.imgur.com/MnH0L85.jpg)
