# spring-boot-reactive

Two reactive Spring Boot services communicating asynchronously over `Flux` / `Mono`, backed by MySQL via reactive repositories. Non-blocking end-to-end.

## Stack

Spring Boot 3 · Spring WebFlux · Java 21 · MySQL · Maven

## What's in here

- REST API using WebFlux annotation-based controllers
- Handler functions for the functional endpoint style (alternative to `@Controller`)
- Reactive repositories — `Flux<T>` / `Mono<T>` returns from data layer through to the response
- Error handling strategies for reactive pipelines

## Run

```bash
./mvnw spring-boot:run
```
