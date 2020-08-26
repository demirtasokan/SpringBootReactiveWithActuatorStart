# SpringBootReactiveWithActuatorStart
Spring Web application using the Spring stack on top of Netty with little configuration from our end. We plugged in Spring Boot's Actuator module,

implementation 'org.springframework.boot:spring-boot-starter-actuator'    //build-gradle file
management.endpoints.jmx.exposure.include=health,info						//application.properties file

localhost:9000/actuator/health												// on postman
