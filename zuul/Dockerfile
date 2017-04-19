FROM java:8-jre
MAINTAINER elviszhang <zhangb2002@163.com>

ADD ./target/zuul-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/zuul-service.jar"]

EXPOSE 5000