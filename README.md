# Java Demo App
This is a simple Spring Boot application with a REST API.

## Run Locally
```
mvn spring-boot:run
```

## Build and Run with Docker
```
docker build -t java-demo-app .
docker run -p 8080:8080 java-demo-app
```

## API Endpoint
```
GET /hello?name=YourName
```
