<div align="center">

# Fidel Shikokoti

### Backend Engineer · Java · Spring Boot · Software Architecture

Building backend systems with an interest in **domain modeling, reliable systems, and maintainable architecture**.

[![GitHub](https://img.shields.io/badge/GitHub-mfalme1k0-181717?style=flat-square\&logo=github)](https://github.com/mfalme1k0)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/)

</div>

---

## About

I'm a backend-focused software developer working primarily with **Java and Spring Boot**.

My earlier work in web and Android development gave me a broad view of application development. I'm now concentrating on backend engineering — particularly **domain-driven design, application architecture, persistence, API design, testing, and system design**.

I enjoy working on problems where the challenge isn't simply making something work, but deciding **where responsibilities belong and how the system should evolve**.

Currently, most of my engineering work is centered around **Ratibu 2.0** and **Matibabu**.

---

## Selected Work

### Ratibu 2.0

**Offline-first business management and financial tracking**

`Java` · `Spring Boot` · `PostgreSQL` · `DDD` · `Offline-First`

Ratibu 2.0 is an ongoing redesign of a small-business management platform.

The system is being designed around domain concepts such as businesses, shops, memberships, workers, clients, bookings, payments, expenses, cash management, and business insights.

The interesting engineering problems are less about CRUD and more about:

* Aggregate boundaries and invariants
* Business-level authorization
* Financial modeling
* Offline operations
* Idempotent synchronization
* Conflict resolution
* Derived business intelligence
* Keeping domain logic independent from infrastructure

The project is intentionally being developed **architecture-first**: define the domain, record the architectural decision, then implement it.

---

### Matibabu

**Offline-first Electronic Medical Records**

`Java` · `Spring Boot` · `PostgreSQL` · `JPA/Hibernate` · `Flyway` · `MapStruct`

A collaborative EMR backend designed for healthcare environments where reliable connectivity cannot be assumed.

Working on Matibabu has been a major part of my transition toward backend engineering and has given me practical experience with:

* Domain modeling
* Application services and use cases
* Persistence boundaries
* REST API design
* PostgreSQL data modeling
* UUIDv7 identifiers
* Database migrations
* Validation and error handling
* Automated testing
* Collaborative Git workflows

The project has also reinforced an important lesson:

> Good backend engineering is as much about boundaries and behavior as it is about frameworks.

---

### Cypher

**Encryption & Decryption in Java**

`Java` · `Cryptography`

A hands-on project exploring cryptographic concepts and the mechanics behind encryption and decryption.

Built primarily as a learning exercise to understand the principles rather than treating cryptography as a black box.

---

## Engineering

My current architectural interests include:

```text
Domain Modeling
      │
      ├── Aggregates & Invariants
      │
      ▼
Application Design
      │
      ├── Use Cases
      ├── Application Services
      └── Dependency Inversion
      │
      ▼
Infrastructure
      │
      ├── Persistence
      ├── PostgreSQL
      └── External Systems
      │
      ▼
API
      │
      └── REST / HTTP
```

I generally prefer:

* **Explicit domain rules** over anemic CRUD models
* **Clear boundaries** over accidental coupling
* **Small, focused abstractions** over abstraction for its own sake
* **Tests around behavior** rather than implementation details
* **Database migrations** over implicit schema changes
* **Application services** for coordinating use cases
* **Dependency inversion** where it provides a meaningful boundary
* **Architecture that serves the domain**, rather than architecture as an end in itself

I'm particularly interested in how these principles hold up when systems have to deal with **failure, concurrency, unreliable networks, changing requirements, and growing complexity**.

---

## Technical Stack

**Primary**

`Java` · `Spring Boot` · `Spring Security` · `PostgreSQL` · `JPA/Hibernate` · `Maven`

**Architecture & Engineering**

`Domain-Driven Design` · `Clean Architecture` · `SOLID` · `REST APIs` · `Application Services` · `Repository Pattern` · `Automated Testing`

**Additional**

`Python` · `Django` · `Kotlin` · `Android` · `JavaScript` · `HTML` · `CSS` · `Bootstrap`

**Tools**

`Git` · `GitHub` · `Linux` · `IntelliJ IDEA` · `Postman`

---

## What I'm Learning

I'm currently going deeper into:

* Java & Spring Boot
* Backend architecture
* Domain-Driven Design
* Database design
* Distributed systems
* Offline-first architecture
* Synchronization and conflict resolution
* Testing strategies
* System design

My direction is increasingly focused on the problems that appear **after the happy path works**.

---

## Engineering Mindset

A few questions I try to ask when designing a system:

> Where does this rule belong?

> What should this component be allowed to know?

> What happens when the network disappears?

> What happens when two operations conflict?

> Can this behavior be tested without starting the entire application?

> If this requirement changes next year, what will have to change with it?

These questions tend to influence my architecture more than any particular framework.

---


## Contribution Activity

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/mfalme1k0/mfalme1k0/main/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/mfalme1k0/mfalme1k0/main/github-contribution-grid-snake.svg"
  />
  <img
    alt="GitHub contribution activity"
    src="https://raw.githubusercontent.com/mfalme1k0/mfalme1k0/main/github-contribution-grid-snake.svg"
  />

</picture>

</div>
### Building software that is understandable today — and changeable tomorrow.

`Java` · `Backend Engineering` · `Architecture` · `System Design`

</div>
