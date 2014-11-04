# Spring Rest service demo with Maven

## How to run
Either

```
> mvn spring-boot:run
```

or

```
> mvn clean package
> java -jar target/gs-rest-service-0.1.0.jar
```

## Test
```
> curl http://localhost:8080/greeting
{"id":1,"content":"Hello, World!"}
> curl "http://localhost:8080/greeting?name=David"
{"id":2,"content":"Hello, David!"}
```
