FROM maven:3.9.6-eclipse-temurin-17 AS dev
WORKDIR /app
COPY . .
RUN chmod +x mvnw
CMD ["./mvnw", "-X", "spring-boot:run"]
