FROM java
COPY target/hello-world-0.0.1-SNAPSHOT.jar /opt/spring-boot-hello-world/hello-world-0.0.1-SNAPSHOT.jar
WORKDIR "/opt/spring-boot-hello-world"
ENTRYPOINT ["java", "-jar", "/opt/spring-boot-hello-world/hello-world-0.0.1-SNAPSHOT.jar"]
