# Project Roadmap & Tracker

## Phase 1: Project Setup
- [x] Initialize Spring Boot Project (Java 17/21)
- [ ] Define Project Metadata (`com.codingshuttle`)
- [ ] Add `spring-boot-starter-web` and `test` dependencies

## Phase 2: Dependency Injection & IoC
- [ ] Create `PaymentService` and `DB` interfaces
- [ ] Annotate services with `@Component`
- [ ] Refactor `OrderService` to use **Constructor Injection**
- [ ] Use `@Primary` or `@Qualifier` for bean resolution

## Phase 3: Configuration & Lifecycle
- [ ] Setup `application.properties`
- [ ] Create `@Configuration` class for third-party beans (e.g., ModelMapper)
- [ ] Implement `@PostConstruct` and `@PreDestroy` hooks

## Phase 4: REST API & Advanced Features
- [ ] Create `ListingController` with `@RestController`
- [ ] Implement search endpoint with optional `@RequestParam`
- [ ] Add Pagination support using `Pageable` and `Page<T>`
- [ ] Write unit tests for service logic
