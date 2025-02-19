FROM tomcat:10.0

MAINTAINER <RAJESH MANDALA>

EXPOSE 4043

WORKDIR /app

COPY /target/test-0.0.1-SNAPSHOT.jar .

ENTRYPOINT ["java", "-jar","test-0.0.1-SNAPSHOT.jar"]

