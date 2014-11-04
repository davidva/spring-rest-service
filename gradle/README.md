# Spring Rest service demo with Gradle

## How to run
Either

```
> gradle bootRun
```

or

```
> gradle build
> java -jar build/libs/gs-rest-service-0.1.0.jar
```

## Test
```
> curl http://localhost:8080/greeting
{"id":1,"content":"Hello, World!"}
> curl "http://localhost:8080/greeting?name=David"
{"id":2,"content":"Hello, David!"}
```
