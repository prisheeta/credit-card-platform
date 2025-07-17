# credit-card-platform
Credit Card Application using SpringBoot

A Spring Boot-based microservice application for managing credit card offerings, applications, and approvals.

---

##  Features (Phase 1)
- View credit card catalog (name, offers, fees, eligibility)
- Apply for a credit card
- Track application status
- REST APIs documented with OpenAPI (Swagger UI)
- In-memory database (H2) for local development

---

## Tech Stack
- **Java** (JDK 17)
- **Spring Boot** 3.x
- **Spring Web**, **Spring Data JPA**
- **H2 Database** (for local testing)
- **springdoc-openapi** (Swagger UI)

---

##  Profiles
- **default** → production-ready configs
- **local** → H2 database for development

### Local profile properties:
- DB: `H2 In-memory`
- Console: `http://localhost:8080/h2-console`
- Swagger: `http://localhost:8080/swagger-ui.html`

---

## How to Run Locally
1. **Clone the repo**
   git clone https://github.com/prisheeta/credit-card-platform.git
   cd credit-card-platform

2. **Run with Maven**
   mvn spring-boot:run -Dspring-boot.run.profiles=local

3. **Access:**
    
    Swagger UI → http://localhost:8080/swagger-ui.html

    H2 Console → http://localhost:8080/h2-console


## High-Level Design:
/docs/hld-diagram.png
