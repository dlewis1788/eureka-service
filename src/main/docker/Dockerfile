FROM openjdk:8u141-jre
VOLUME /tmp
ADD eureka-service-0.0.1-SNAPSHOT.jar eureka-service-0.0.1-SNAPSHOT.jar
RUN sh -c 'touch /eureka-service-0.0.1-SNAPSHOT.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /eureka-service-0.0.1-SNAPSHOT.jar" ]