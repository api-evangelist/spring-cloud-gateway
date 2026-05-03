# Spring Cloud Gateway

Spring Cloud Gateway provides an intelligent, programmable router built on Spring WebFlux that serves as the entry point to microservice architectures. It offers routing, predicate evaluation, filter chaining, load balancing, circuit breaking, rate limiting, and runtime route management through an Actuator API.

**URL:** https://spring.io/projects/spring-cloud-gateway

## Tags

API Gateway, Circuit Breaker, Load Balancing, Microservices, Rate Limiting, Routing, Spring, Spring WebFlux

## APIs

### Spring Cloud Gateway Actuator API

Runtime management API for Spring Cloud Gateway exposing endpoints for retrieving, creating, updating, and deleting route definitions. Also provides access to global filters, route filter factories, route predicate factories, and cache refresh capabilities.

**Human URL:** https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api  
**Base URL:** http://localhost:8080/actuator/gateway

**Tags:** Actuator, API Gateway, Filters, Management, Monitoring, Routes

**Properties:**
- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api)
- [OpenAPI](openapi/spring-cloud-gateway-actuator-openapi.yml)
- [JSON Schema - Route](json-schema/spring-cloud-gateway-route-schema.json)
- [JSON Structure](json-structure/spring-cloud-gateway-route-structure.json)
- [JSON-LD Context](json-ld/spring-cloud-gateway-context.jsonld)
- [Spectral Rules](rules/spring-cloud-gateway-rules.yml)
- [Naftiko Capability](capabilities/api-gateway-management.yaml)

### Spring Cloud Gateway Core

Core routing and filtering capabilities including predicate factories (Path, Host, Method, Header, Query, Cookie, Weight, RemoteAddr), gateway filter factories (AddRequestHeader, RewritePath, RequestRateLimiter, CircuitBreaker, Retry), and global filters for proxying requests to downstream services.

**Human URL:** https://spring.io/projects/spring-cloud-gateway

**Tags:** API Gateway, Filtering, Load Balancing, Predicates, Routing

**Properties:**
- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/)
- [Getting Started](https://spring.io/projects/spring-cloud-gateway#learn)
- [GitHub](https://github.com/spring-cloud/spring-cloud-gateway)
- [Releases](https://github.com/spring-cloud/spring-cloud-gateway/releases)

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|------|-------------|
| [spring-cloud-gateway-actuator-openapi.yml](openapi/spring-cloud-gateway-actuator-openapi.yml) | Gateway Actuator API for runtime route management |

### JSON Schemas

| Schema | Description |
|--------|-------------|
| [spring-cloud-gateway-route-schema.json](json-schema/spring-cloud-gateway-route-schema.json) | RouteDefinition schema including predicates and filters |

### JSON Structures

| Structure | Description |
|-----------|-------------|
| [spring-cloud-gateway-route-structure.json](json-structure/spring-cloud-gateway-route-structure.json) | Route, predicate, and filter structure documentation |

### JSON-LD Contexts

| Context | Description |
|---------|-------------|
| [spring-cloud-gateway-context.jsonld](json-ld/spring-cloud-gateway-context.jsonld) | Spring Cloud Gateway linked data context |

### Examples

| Example | Description |
|---------|-------------|
| [spring-cloud-gateway-create-route-example.json](examples/spring-cloud-gateway-create-route-example.json) | Create a new gateway route with rate limiting |
| [spring-cloud-gateway-list-routes-example.json](examples/spring-cloud-gateway-list-routes-example.json) | List all configured gateway routes |

### Spectral Rules

| Ruleset | Description |
|---------|-------------|
| [spring-cloud-gateway-rules.yml](rules/spring-cloud-gateway-rules.yml) | API design rules for Spring Cloud Gateway conventions |

### Naftiko Capabilities

| Capability | Description |
|------------|-------------|
| [capabilities/api-gateway-management.yaml](capabilities/api-gateway-management.yaml) | API gateway management workflow (route CRUD, refresh, filter discovery) |
| [capabilities/shared/spring-cloud-gateway-actuator.yaml](capabilities/shared/spring-cloud-gateway-actuator.yaml) | Shared Gateway Actuator API consumer definition |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [spring-cloud-gateway-vocabulary.yml](vocabulary/spring-cloud-gateway-vocabulary.yml) | Spring Cloud Gateway domain vocabulary and terminology |

## Common Properties

- [Website](https://spring.io/projects/spring-cloud-gateway)
- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/)
- [GitHub](https://github.com/spring-cloud/spring-cloud-gateway)
- [GitHub Organization](https://github.com/spring-cloud)
- [Issues](https://github.com/spring-cloud/spring-cloud-gateway/issues)
- [Releases](https://github.com/spring-cloud/spring-cloud-gateway/releases)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud-gateway)
- [Maven Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-gateway-server)

## Maintainers

**Name:** Kin Lane  
**Email:** kin@apievangelist.com
