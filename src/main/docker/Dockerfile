FROM zhouwei/docker-test
VOLUME /tmp
EXPOSE 9090 9091
ADD docker-test-1.0.0.jar app.jar
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
