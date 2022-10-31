FROM java:8
VOLUME /tmp
ADD yst-nuskin-gateway.jar yst-nuskin-gateway.jar
EXPOSE 8201
ENTRYPOINT ["java", "Dspring.profiles.active=dokcer", "-jar", "yst-nuskin-gateway.jar"]
