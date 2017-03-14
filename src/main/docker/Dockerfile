FROM frolvlad/alpine-oraclejdk8:slim
VOLUME /tmp
ADD teligen-microservice-eureka.jar teligen-microservice-eureka.jar
RUN sh -c 'touch /teligen-microservice-eureka.jar'
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS -jar /teligen-microservice-eureka.jar" ]