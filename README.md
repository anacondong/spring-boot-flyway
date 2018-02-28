## spring-boot-flyway

#Install Maven,Java8,flyway

#run
$mvn clean install </br>
$cd target</br>
$mvn spring-boot:run</br>

#Ref: https://github.com/spring-projects/spring-boot

== Spring Boot Flyway Sample

This sample demonstrates the flyway auto-configuration support.

You can look at `http://localhost:8080/actuator/flyway` to review the list of scripts.

This sample also enables the H2 console (at `http://localhost:8080/h2-console`)
so that you can review the state of the database (the default jdbc url is
`jdbc:h2:mem:testdb`).