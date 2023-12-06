FROM openjdk:11-jre-slim
LABEL maintainer="Biniam.Solomon"
EXPOSE 8080
VOLUME /tmp
ADD target/Customer-Registrationr.jar Customer-Registration.jar
ENTRYPOINT ["java", "-jar", "/Customer-Registration.jar"]