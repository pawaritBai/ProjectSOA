FROM openjdk:17-jdk-slim

WORKDIR /app

# คัดลอกไฟล์ .war ไปยัง Container
COPY target/project-0.0.1-SNAPSHOT.war app.war

# เปิดพอร์ต 8080
EXPOSE 8080

# รัน Spring Boot Application (WAR)
ENTRYPOINT ["java", "-jar", "app.war"]

