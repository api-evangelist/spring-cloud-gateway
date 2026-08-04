# Spring Cloud Gateway (spring-cloud-gateway)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Spring Cloud Gateway provides an intelligent, programmable router built on Spring WebFlux that serves as the entry point to microservice architectures. It offers routing, predicate evaluation, filter chaining, load balancing, circuit breaking, rate limiting, and runtime route management through an Actuator API.

**APIs.json:** [https://spring.io/projects/spring-cloud-gateway](https://spring.io/projects/spring-cloud-gateway)

## Tags

- API Gateway
- Circuit Breaker
- Load Balancing
- Microservices
- Rate Limiting
- Routing
- Spring
- Spring WebFlux

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Spring Cloud Gateway Actuator API

Runtime management API for Spring Cloud Gateway exposing endpoints for retrieving, creating, updating, and deleting route definitions. Also provides access to global filters, route filter factories, route predicate factories, and cache refresh capabilities.

- **Human URL:** [https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api)
- **Base URL:** `http://localhost:8080/actuator/gateway`

#### Tags

- Actuator
- API Gateway
- Filters
- Management
- Monitoring
- Routes

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/#actuator-api)
- [OpenAPI](openapi/spring-cloud-gateway-actuator-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/spring-cloud-gateway-route-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/spring-cloud-gateway-route-structure.json)
- [J S O N L D Context](json-ld/spring-cloud-gateway-context.jsonld)
- [Spectral Rules](rules/spring-cloud-gateway-rules.yml)

### Spring Cloud Gateway Core

Core routing and filtering capabilities including predicate factories (Path, Host, Method, Header, Query, Cookie, Weight, RemoteAddr), gateway filter factories (AddRequestHeader, RewritePath, RequestRateLimiter, CircuitBreaker, Retry), and global filters for proxying requests to downstream services.

- **Human URL:** [https://spring.io/projects/spring-cloud-gateway](https://spring.io/projects/spring-cloud-gateway)
- **Base URL:** `http://localhost:8080`

#### Tags

- API Gateway
- Filtering
- Load Balancing
- Predicates
- Routing

#### Properties

- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/)
- [Getting Started](https://spring.io/projects/spring-cloud-gateway#learn)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-gateway)
- [Releases](https://github.com/spring-cloud/spring-cloud-gateway/releases)
- [Postman Collection](collections/spring-cloud-gateway-actuator.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/spring-cloud-gateway-actuator.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://spring.io/projects/spring-cloud-gateway)
- [Documentation](https://docs.spring.io/spring-cloud-gateway/docs/current/reference/html/)
- [Git Hub](https://github.com/spring-cloud/spring-cloud-gateway)
- [GitHub Organization](https://github.com/spring-cloud)
- [Issues](https://github.com/spring-cloud/spring-cloud-gateway/issues)
- [Releases](https://github.com/spring-cloud/spring-cloud-gateway/releases)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/spring-cloud-gateway)
- [Maven  Repository](https://mvnrepository.com/artifact/org.springframework.cloud/spring-cloud-gateway-server)
- [Vocabulary](vocabulary/spring-cloud-gateway-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
