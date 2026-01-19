FROM openjdk:21-ea-jdk-slim

LABEL "org.opencontainers.image.authors" = "example.com"

COPY target/accounts-0.0.1-SNAPSHOT.jar accounts-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java", "-jar", "accounts-0.0.1-SNAPSHOT.jar"]