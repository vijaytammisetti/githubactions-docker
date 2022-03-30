FROM openjdk:11
EXPOSE 8080
ADD target/githubactions.jar githubactions.jar
ENTRYPOINT ["java","-jar","/githubactions.jar"]
