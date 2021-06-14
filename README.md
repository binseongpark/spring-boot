# spring-boot

나중에 마크다운 다시 정리하기
### spring-boot actuator prometheus & grafana

dependency 2개 추가
spring-boot-starter-actuator
micrometer-registry-prometheus -> 이것을 추가해야만 엔드포인트에 프로메테우스 보임

application.properties 에 아래 한줄 추가
management.endpoints.web.exposure.include=health,info,prometheus

### spring security

### websocket
