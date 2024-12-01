#가져올 이미지
FROM openjdk:21-jdk-slim

#컨테이너화 될 때 명령이 실행되는 디렉토리
WORKDIR /app

#좌측 경로의 jar파일을 WORKDIR의 sample.jar라는 파일명으로 복사
COPY build/sample.jar ./sample.jar

#명령어 실행 시 필수값(반드시 실행되는 명령어이고 대체 불가)
ENTRYPOINT ["java", "-jar", "sample.jar"]