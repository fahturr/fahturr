<h1 align="center">Hi, I'm Fahtur 👋</h1>

<p align="center">
  <b>Backend engineer in Jakarta</b> building reliable payment and API backends in Java,<br>
  and shipping full-stack web apps with Nuxt and TypeScript.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white" alt="Quarkus" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Nuxt-00DC82?style=for-the-badge&logo=nuxt&logoColor=white" alt="Nuxt" />
</p>

---

## About me

- 4 years building backend systems, mostly in **banking and fintech**
- I care about the unglamorous parts that break in production: **duplicate charges, forged or replayed webhooks, out-of-order events, flaky third-party APIs**
- Comfortable with **Spring Boot** and **Quarkus**, REST API design, and shipping with Docker and CI
- Also build the frontend when a project needs it: **Nuxt / Vue** with **TypeScript**

## Featured projects

### 💳 [payment-gateway-integration](https://github.com/fahturr/payment-gateway-integration)

A Spring Boot service for Midtrans payments, built to survive real-world failures:

- **Idempotency-Key** support, enforced by a database constraint, so client retries never double-charge
- **Signature-verified, deduplicated webhooks** with amount checks
- **Forward-only state machine**, so late or replayed events cannot corrupt payment status
- **Retry with exponential backoff** for provider calls, plus a **reconciliation job** for missed notifications

`Java 21` · `Spring Boot 3` · `PostgreSQL` · `Flyway` · `Docker Compose` · `GitHub Actions`

### 🚆 [peron](https://github.com/fahturr/peron)

A responsive web app for live departures on Jakarta's KRL Commuter Line:

- **Departure boards** with live countdowns and line/destination filters, plus a train view showing where each train is on its route
- **Hand-built SVG transit map** of the network, including the Cikarang loop, with clickable stations
- **Partner API client** behind a server API layer, with caching and a clearly labelled simulated timetable when no API is configured
- **Light/dark/system themes**, favourite stations, and a mobile-first layout

`Nuxt 4` · `Vue 3` · `TypeScript` · `Nitro` · `SVG`

## More projects

| Project | About | Stack |
|---|---|---|
| [foodies-crm](https://github.com/fahturr/foodies-crm) | CRM application written in Go | <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |
| [flutter-clean-architecture](https://github.com/fahturr/flutter-clean-architecture) | Flutter app organized with Clean Architecture | <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter" /> |
| [noobee-bootcamp-golang](https://github.com/fahturr/noobee-bootcamp-golang) | Go exercises and projects from a Golang bootcamp | <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" /> |

## Open to

Freelance and contract backend work:

- Payment gateway and third-party API integrations
- REST APIs with Spring Boot or Quarkus
- Reliability work: idempotency, retries, webhook handling, reconciliation
- Full-stack web apps with Nuxt / Vue and TypeScript

## Get in touch

<p>
  <a href="https://www.linkedin.com/in/fahtur/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:fahtur.rf@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
