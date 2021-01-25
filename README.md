# AWS-mobile-app

- 외부 강의 
  > 동서대학교 센텀 캠퍼스 12층 클라우드 혁신 센터 ( 부산 )
- [참고 페이지1](http://devops.piljoong.com/)
- [참고 페이지2](https://www.slideshare.net/awskorea/aws-amplify-aws-aws-summit-seoul-2019)

## **사용할 기술**
- Node.js v8
- Amplify 
- Expo
- React Native
- AppSync(GraphQL)

### AWS Amplify - 통합된 개발자 경험
가장 널리 사용되는 OS 플랫폼 및 프레임워크에 대한 지원을 해줌.  
- init  
- add auth  
- add storage  
- add api  
- add function 

## AppSync(GraphQL)
- **API를 위한 쿼리 언어**    
- **관리되는 GraphQL 게이트 웨이**  
  - 스키마 정의 언어(SDL)를 사용하여 API의 모양을 정의  
  - 다른 AWS 리소스를 참조하는 데이터 소스 첨부  
  - 데이터 소스에서 데이터를 가져와 필드에 첨부하는 해석기(Resolver) 작성     
- **실시간 데이터 브로커**  
  - 곧바로 모든 변형을 위한 구독 -> WebSocket MQTT를 통한 안정적인 메시지 전달  

