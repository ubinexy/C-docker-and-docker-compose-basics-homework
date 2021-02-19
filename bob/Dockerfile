FROM java:8

COPY build/libs/bob-0.0.1-SNAPSHOT.jar bob.jar

ENTRYPOINT ["java","-jar","/bob.jar"]

# 暴露端口
EXPOSE 8081
