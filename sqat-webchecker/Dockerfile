FROM openjdk:11
EXPOSE 8080
ADD sqat-webchecker/target/webcheck.jar webcheck.jar
ENTRYPOINT ["java","-jar","/webcheck.jar"]
