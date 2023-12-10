FROM openjdk:17
EXPOSE 8081
ADD target/API_Gatway_Server-0.0.1-SNAPSHOT.jar API_Gatway_Server-0.0.1-SNAPSHOT.jar
ADD src/main/resources/application.properties application.properties
ENTRYPOINT ["java", "-jar" , "API_Gatway_Server-0.0.1-SNAPSHOT.jar"]