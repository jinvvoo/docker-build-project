FROM adoptopenjdk/openjdk11
#아규먼트약자, 경로설정할때 arg명령어 사용, 일반적으로 대문자로, jar파일을 문자열형태로
ARG JAR_FILE_PATH=build/libs/*.jar
COPY ${JAR_FILE_PATH} app.jar

ENTRYPOINT ["java", "-jar","app.jar"]