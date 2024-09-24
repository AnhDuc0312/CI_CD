# Sử dụng image Java 17
FROM openjdk:17-jdk-slim

# Đặt thư mục làm việc trong container
WORKDIR /app

# Copy Gradle build output từ dự án
COPY ../build/libs/cms-0.0.1-SNAPSHOT.jar /app/cms.jar

# Expose cổng cho ứng dụng Spring Boot
EXPOSE 8080

# Chạy ứng dụng Spring Boot
ENTRYPOINT ["java", "-jar", "/app/cms.jar"]
