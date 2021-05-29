FROM openjdk
COPY target/*.jar /
EXPOSE 8091
ENTRYPOINT ["java","-jar","/javaE2EDemo-0.0.1-SNAPSHOT.jar"]
RUN apk update && apk add bash