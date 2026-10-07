<h1 align="center">Hi, I'm Fahtur 👋</h1>

<p align="center">
  <b>Backend engineer in Jakarta</b> building reliable payment and API backends in Java.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Quarkus-4695EB?style=for-the-badge&logo=quarkus&logoColor=white" alt="Quarkus" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## About me

- 4 years building backend systems, mostly in **banking and fintech**
- I care about the unglamorous parts that break in production: **duplicate charges, forged or replayed webhooks, out-of-order events, flaky third-party APIs**
- Comfortable with **Spring Boot** and **Quarkus**, REST API design, and shipping with Docker and CI

## Featured project

### 💳 [payment-gateway-integration](https://github.com/fahturr/payment-gateway-integration)

A Spring Boot service for Midtrans payments, built to survive real-world failures:

- **Idempotency-Key** support, enforced by a database constraint, so client retries never double-charge
- **Signature-verified, deduplicated webhooks** with amount checks
- **Forward-only state machine**, so late or replayed events cannot corrupt payment status
- **Retry with exponential backoff** for provider calls, plus a **reconciliation job** for missed notifications

`Java 21` · `Spring Boot 3` · `PostgreSQL` · `Flyway` · `Docker Compose` · `GitHub Actions`

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

## Get in touch

<p>
  <a href="https://www.linkedin.com/in/fahtur/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:fahtur.rf@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>
