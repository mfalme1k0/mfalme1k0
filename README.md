Fidel Shikokoti

Software Engineer · Backend · Java / Kotlin

I build software with a growing focus on backend engineering, system design, and maintainable application architecture.

My work spans Java and Spring Boot backend systems, Kotlin/Android applications, and web platforms. I'm particularly interested in understanding how software systems are structured — from domain models and business rules to persistence, APIs, security, testing, and offline-first design.

I'm currently focused on building software that is not only functional, but structured, testable, maintainable, and understandable.

---

What I'm About

- Building backend systems with Java and Spring Boot
- Designing domain models and application boundaries
- Practicing Clean Architecture, SOLID, and separation of concerns
- Working with PostgreSQL, SQLite, JPA, and Hibernate
- Designing and consuming REST APIs
- Writing automated tests and handling failure cases
- Exploring offline-first and synchronization-oriented systems
- Building Android applications with Kotlin and Jetpack Compose
- Working with TypeScript, Next.js, Express, and modern web development
- Developing in Linux with Git-based engineering workflows

---

Featured Work

Matibabu

Offline-First Electronic Medical Records Platform

Java · Spring Boot · PostgreSQL / SQLite · JPA / Hibernate · Spring Security

Matibabu is a collaborative healthcare information system designed around the realities of healthcare facilities where network connectivity cannot always be assumed.

The backend currently covers areas including:

- Patient management
- Clinical encounters and medical records
- Clinical observations, diagnoses, vitals, and treatments
- Medicines and ATC classification
- Referrals
- Facilities and departments
- Clinician authentication and role-based authorization
- Local SQLite persistence
- Database migrations with Flyway
- Repository abstractions and adapters
- Automated testing
- Initial offline synchronization architecture

The project uses a layered architecture in which domain rules remain independent from frameworks, databases, and transport mechanisms.

Matibabu has been an important part of my transition from building individual applications toward thinking about larger systems, domain boundaries, persistence, security, synchronization, and long-term maintainability.

---

TraceFinder

Java Log Analysis & Security-Focused Reporting

Java · Maven · JUnit

TraceFinder is a command-line log analysis and reporting tool built around defensive processing of structured log data.

It includes:

- Streaming and bounded file processing
- Strict UTF-8 handling
- File and line-size limits
- Configurable severity rules
- Time-window filtering
- Structured exception handling
- Separation between parsing, analysis, and reporting
- Defensive handling of malformed and hostile input
- Extensive automated tests

The project contains dedicated test fixtures for cases such as malformed UTF-8, delimiter injection, invalid timestamps, oversized input, duplicate fields, and invalid severity rules.

This project reflects my interest in robust software behaviour, defensive programming, and understanding what happens when systems receive input that doesn't behave as expected.

---

Ratibu 2.0

Offline-First Business Management Platform

Java · Spring Boot · PostgreSQL · JPA · Spring Security · Flyway

Ratibu 2.0 is an architecture-first business management platform for small businesses.

The current work is focused on establishing the domain and application foundations before expanding into client applications.

The domain currently considers concepts such as:

- Businesses and shops
- Users and memberships
- Workers and clients
- Catalogues and services
- Bookings
- Payments and expenses
- Financial events
- Cash management
- Business insights

The system is being designed around stable identifiers, idempotent synchronization, aggregate boundaries, and explicit domain rules so that offline-capable clients can be introduced without coupling the core business logic to a particular interface or persistence mechanism.

---

Ratibu

Android Appointment Booking Application

Kotlin · Jetpack Compose · Firebase

Ratibu is an individual Android application for appointment and service-provider management.

The application includes:

- User registration and authentication
- Service-provider profiles
- Appointment booking
- Upcoming and current bookings
- Real-time chat
- Push notifications
- Appointment reminders
- Local caching
- Network-aware result handling
- Image uploads
- Location features

The application follows a repository-oriented architecture connecting Compose UI, ViewModels, repositories, Firebase services, and local state.

It remains an important part of my experience with Kotlin, Android application architecture, asynchronous operations, and mobile product development.

---

Nyumbani

Real Estate Platform

Next.js · TypeScript · Express · PostgreSQL · JWT · RBAC

Nyumbani is a dual-sided real-estate platform designed for tenants and property owners or agents.

The system combines a web frontend with a backend API and includes authentication, role-based access control, property workflows, and PostgreSQL persistence.

The project gave me practical experience working across the boundary between frontend applications, backend APIs, authentication, authorization, and relational data.

---

GreenDay Bank

Java Command-Line Banking Application

Java · OOP · BigDecimal

GreenDay Bank is a collaborative Java banking application focused on object-oriented design and financial operations.

The application models:

- User authentication
- Savings accounts
- Transfers
- Investment accounts
- Investment funds
- Financial validation
- Monetary calculations

The project provided practical experience with object-oriented modelling, service boundaries, validation, exceptions, and financial state management.

---

Engineering

I'm particularly interested in keeping business logic independent from infrastructure.

A simplified representation of the architecture I practice:

                         CLIENT
                           │
                           ▼
                    ┌──────────────┐
                    │   REST API   │
                    └──────┬───────┘
                           │
                           ▼
                 ┌──────────────────┐
                 │   APPLICATION    │
                 │                  │
                 │    Use Cases     │
                 │    Services      │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │      DOMAIN      │
                 │                  │
                 │ Entities         │
                 │ Business Rules   │
                 │ Value Objects    │
                 └────────┬─────────┘
                          │
                          ▼
                 ┌──────────────────┐
                 │  INFRASTRUCTURE  │
                 │                  │
                 │ PostgreSQL       │
                 │ JPA / Hibernate  │
                 │ External APIs    │
                 └──────────────────┘

The purpose isn't to apply architecture patterns for their own sake.

The goal is to make systems where business rules remain understandable, boundaries are explicit, and changes do not unnecessarily ripple through the entire application.

---

Technical Stack

Backend

"Java" "Spring Boot" "Spring MVC" "Spring Data JPA" "Hibernate" "REST APIs" "Maven"

Architecture & Engineering

"Clean Architecture" "Domain Modeling" "SOLID" "Separation of Concerns" "Repository Pattern" "Application Services"

Databases

"PostgreSQL" "SQLite" "SQL" "JPA" "Hibernate" "Flyway"

Security

"Spring Security" "JWT" "Authentication" "Authorization" "RBAC"

Mobile

"Kotlin" "Android" "Jetpack Compose" "Firebase"

Web

"TypeScript" "Next.js" "React" "Express" "HTML" "CSS"

Testing & Tools

"JUnit 5" "Mockito" "Git" "GitHub" "IntelliJ IDEA" "Linux" "Postman"

---

GitHub

<div align="center"><img src="https://github-readme-stats.vercel.app/api?username=mfalme1k0&show_icons=true&hide_border=true&theme=transparent&title_color=00D9A5&icon_color=00D9A5&text_color=8B949E&bg_color=00000000" height="170"/><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mfalme1k0&layout=compact&hide_border=true&theme=transparent&title_color=00D9A5&text_color=8B949E&bg_color=00000000" height="170"/></div>---

Contribution Activity

<div align="center"><picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="./github-contribution-grid-snake-dark.svg"
  /><source
media="(prefers-color-scheme: light)"
srcset="./github-contribution-grid-snake.svg"
/>

<img
alt="GitHub contribution activity"
src="./github-contribution-grid-snake.svg"
/>
</picture>

</div>---

Currently Focused On

Backend Engineering

Going deeper into:

- Java
- Spring Boot
- PostgreSQL
- REST API design
- JPA / Hibernate
- Testing
- Domain modeling
- Clean Architecture
- System Design
- Offline-first systems

My Current Direction

WEB DEVELOPMENT
       │
       ▼
ANDROID / KOTLIN
       │
       ▼
JAVA
       │
       ▼
BACKEND DEVELOPMENT
       │
       ▼
SPRING BOOT
       │
       ▼
SOFTWARE ARCHITECTURE
       │
       ▼
SYSTEM DESIGN

I'm deliberately moving toward becoming a stronger backend/software engineer, while retaining the broader development experience I've gained through web and mobile projects.

---

Engineering Mindset

I believe good engineering goes beyond making an application work.

I'm learning to ask:

Can I understand this code six months from now?

Can another developer understand it without me explaining everything?

Can business rules change without rewriting the entire system?

Can this behaviour be tested independently?

What happens when something fails?

Those questions increasingly influence how I approach my projects.

---

Open to Opportunities

I'm interested in opportunities where I can:

- Contribute to real software products
- Work alongside experienced developers
- Grow as a backend engineer
- Learn production engineering practices
- Work with Java and Spring Boot
- Contribute to meaningful technical projects
- Continue developing my understanding of system architecture

I'm particularly interested in backend development, software engineering, and collaborative engineering environments.

---

<div align="center">Building systems, learning deeply, improving continuously.

Java · Backend · Architecture · Problem Solving

<br><a href="https://github.com/mfalme1k0">
  <img src="https://img.shields.io/badge/GitHub-mfalme1k0-181717?style=flat&logo=github" alt="GitHub">
</a><a href="https://www.linkedin.com/in/shikokoti-ikoha">
  <img src="https://img.shields.io/badge/LinkedIn-Fidel%20Shikokoti-0A66C2?style=flat&logo=linkedin" alt="LinkedIn">
</a><br><br>

"mfalme1k0"

</div>