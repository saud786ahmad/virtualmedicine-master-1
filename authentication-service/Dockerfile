FROM openjdk:11-jre-slim
ADD ./target/authentication-service-0.0.1-SNAPSHOT.war /usr/src/authentication-service-0.0.1-SNAPSHOT.war
WORKDIR usr/src
ENTRYPOINT ["java","-war", "authentication-service-0.0.1-SNAPSHOT.war"]
