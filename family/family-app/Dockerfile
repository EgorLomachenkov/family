FROM openjdk:21-jdk
ARG JAR_FILE=var/lib/jenkins/workspace/family-docker/jenkins-test/family/family-app/target/*.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
