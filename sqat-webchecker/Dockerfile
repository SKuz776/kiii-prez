FROM openjdk:11
EXPOSE 8080
ADD target/webcheck.jar webcheck.jar
ENTRYPOINT ["java","-jar","/webcheck.jar"]
