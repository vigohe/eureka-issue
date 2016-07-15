FROM nimmis/java-centos:openjdk-8-jre
ADD *.jar /app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]