FROM arm64v8/eclipse-termurinL17-jdk-focal

ARG JAR_FILE=build/lib/*.jar

COPY ${JAR_FILE} app.jar

ENTRYPOINT ["java","-jar","-Duser.timezone=Asia/Seoul","/app.jar"]