FROM java:8
VOLUME /tmp
EXPOSE 8080
ADD eis-loginapp-1.0.0-SNAPSHOT.jar eis-loginapp.jar
RUN sh -c 'touch /eis-loginapp.jar'
ENTRYPOINT ["java","-jar","eis-loginapp.jar"]