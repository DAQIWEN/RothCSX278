FROM openjdk:8
WORKDIR /app/jhipster-project
ADD ./build/libs/project-2-0.0.1-SNAPSHOT.war . 
MAINTAINER brittany.d.roth@vanderbilt.edu

EXPOSE 8080
CMD java -jar project-2-0.0.1-SNAPSHOT.war --spring.profiles.active=dev,swagger
