FROM openjdk:11
EXPOSE 8080
RUN mvn -f sqat-webchecker/pom.xml clean package
ADD target/webcheck.jar webcheck.jar
ENTRYPOINT ["java","-jar","/webcheck.jar"]
