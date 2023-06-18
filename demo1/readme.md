## Notes for demo user



* ./mvnw spring-boot:run  
OR  
* ./mvnw clean package
* java -jar target/gs-rest-service-0.1.0.jar
* http://localhost:8080/greeting?name=User  
* http://localhost:8080/actuator/health
OCP Deploy  
* mvn clean install -Ddekorate.build=true 
### Health Checks
* https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html#actuator.endpoints.health.auto-configured-health-indicators  
* https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html#actuator.endpoints.kubernetes-probes
* https://www.baeldung.com/spring-boot-actuator-enable-endpoints


