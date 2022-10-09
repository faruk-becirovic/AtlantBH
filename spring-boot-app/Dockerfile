FROM maven:3-eclipse-temurin-8

RUN mkdir app
WORKDIR /app
RUN git clone https://github.com/kkenan/basic-microservices.git
WORKDIR /app/basic-microservices/spring-boot-app
RUN mvn clean package
RUN mv /app/basic-microservices/spring-boot-app/target/spring-boot-app-1.0-SNAPSHOT.jar /app/app.jar
WORKDIR /app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]