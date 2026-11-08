# Fidel Shikokoti

### Backend-focused Software Developer · Java · Spring Boot

I build backend systems in Java and Spring Boot, with a focus on domain modeling, persistence, and testing. Most of my recent work is on software for places where the network can't be trusted: clinics, small businesses, and shared tools that have to stay consistent when things go wrong.

I'm looking for a team where I can contribute to real software and learn from experienced engineers.

[![GitHub](https://img.shields.io/badge/GitHub-mfalme1k0-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mfalme1k0) [![LinkedIn](https://img.shields.io/badge/LinkedIn-shikokoti--ikoha-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shikokoti-ikoha)

---

## Featured Work

| Project | What it is | Stack | Status |
| --- | --- | --- | --- |
| [**Matibabu**](https://github.com/mfalme1k0/matibabu) | Offline-first EMR for low-connectivity health centres | Java, Spring Boot, JPA, Flyway, SQLite, PostgreSQL | Core clinical backend done; sync in progress |
| [**Multi-user Rental Tracker**](https://github.com/mfalme1k0/multi-user-rental-tracker) | Shared rental library CLI, built with a team of three | Java 21, SQLite, ArchUnit, Docker | Complete; 100% line coverage |
| [**Ratibu 2.0**](https://github.com/mfalme1k0/Ratibu2.0) | Offline-first business management backend | Java 21, Spring Boot, PostgreSQL, Flyway | Early implementation; architecture documented |
| [**Ratibu**](https://github.com/mfalme1k0/Ratibu) | Android appointment-booking app (solo project) | Kotlin, Jetpack Compose, Firebase | Released through v1.0.30 |

---

### Matibabu: Offline-First EMR for Low-Connectivity Health Centres

`Java` `Spring Boot` `Spring Security` `JPA/Hibernate` `MapStruct` `Flyway` `SQLite` `PostgreSQL` `GitHub Actions`

An electronic medical record system for clinics that can't rely on internet access. The repository is under my account, and other developers contribute through pull requests.

**What's implemented**

- Patients, encounters (with an enforced `ACTIVE → DISCHARGED / CANCELLED` lifecycle), medical records, and clinical data (vitals, observations, diagnoses, treatments)
- Clean Architecture / DDD layering: the domain layer has no dependency on Spring or persistence
- Session-based authentication with Spring Security
- Flyway migrations, SQLite for local/offline use and PostgreSQL for the server
- Central exception handling, automated tests, and ADRs for major decisions

**My contributions include** facility and department modelling, patient bean refactors, repository adapter cleanup, seeded starter medicines, CORS configuration, and the initial PWA frontend design.

**Where it stands:** the core clinical workflow works. The frontend is in progress, remote synchronization is the next milestone, and DHIS2 integration is planned after that.

---

### Multi-user Rental Tracker: A Shared Rental Library

`Java 21` `SQLite` `Maven` `ArchUnit` `JUnit 5` `Docker` `Logback`

A command-line application where multiple users register, list items, browse each other's listings, rent them, and confirm returns. Built as a team of three, with reviewed pull requests throughout.

- **Five-layer architecture enforced by ArchUnit tests**, so layering rules fail the build instead of living in a wiki
- **Rules enforced in the service layer and again in the database**: ownership checks, an item state machine (`AVAILABLE`, `RENTED`, `UNLISTED`), `CHECK` constraints, foreign keys, and a partial unique index allowing at most one active rental per item
- Password hashing, centralized validation, and structured logging that never records credentials
- **100% line coverage and 99.7% branch coverage** (the one missed branch is a compiler-generated try-with-resources path, documented in the README)
- Dockerized with a persistent database volume

I worked on it as one of three developers, including the CI workflow and its protections.

---

### Ratibu 2.0: Offline-First Business Management

`Java 21` `Spring Boot` `PostgreSQL` `Flyway` `Spring Security`

A backend for small businesses covering shops, workers, clients, bookings, payments, expenses, and cash reconciliation. I started with the domain and architecture decisions (aggregates, membership and authorization, financial rules, sync and conflict resolution) and documented them as ADRs before writing feature code.

**Implemented so far:** the Business, Shop, and Account vertical slices, each taken from domain through persistence, application service, REST API, and tests. Client-generated stable IDs make business creation idempotent, which is the first piece of the offline sync design.

**Designed but not yet built:** the remaining aggregates, JWT authentication, and the synchronization engine.

---

### Ratibu: Android Appointment Booking App

`Kotlin` `Jetpack Compose` `Firebase` `WorkManager`

A solo project for connecting customers with service providers: authentication, provider discovery, appointment booking and management, in-app chat, notifications, and reminders. It went through many iterations and versioned releases (current release v1.0.30), with CI workflows in the repository.

---

## Technical Skills

| Area | Skills |
| --- | --- |
| **Backend** | Java, Spring Boot, Spring Security, Spring Data JPA, Hibernate, MapStruct, REST API design, Maven |
| **Data** | PostgreSQL, SQLite, SQL, Flyway migrations, schema constraints |
| **Quality** | JUnit 5, ArchUnit, JaCoCo, integration testing against real databases, structured logging |
| **Practices** | Domain modeling, Clean Architecture, ADRs, Git workflows with pull requests, GitHub Actions, Docker |
| **Also used** | Kotlin, Jetpack Compose, Firebase, TypeScript, Next.js, Express |

---

## How I Work

I try to put each rule in the right place: business rules in the domain, orchestration in services, and integrity guarantees in the database. I write down significant decisions as ADRs, and I test behavior against real databases instead of relying on mocks alone.

---

## Currently Learning

Offline-first synchronization, conflict resolution, distributed systems, and system design.

---

## Open to Opportunities

Backend and software developer roles, especially Java and Spring Boot, on teams that value testing and clear architecture.

---

## Contribution Activity

<picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/mfalme1k0/mfalme1k0/output/pacman-contribution-graph-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/mfalme1k0/mfalme1k0/output/pacman-contribution-graph.svg">
    <img alt="Pac-Man eating my contribution graph" src="https://raw.githubusercontent.com/mfalme1k0/mfalme1k0/output/pacman-contribution-graph.svg">
</picture>