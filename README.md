# Hi, I'm Omprakash Seervi 👋

**Tech Lead / Software Engineer** · Back-end Development · Technical Leadership · Solution Architecture
📍 Bengaluru, India

I have about 12 years of experience building back-end systems for FinTech, Retail and Enterprise. I design and ship scalable, secure, high-performance systems: microservices, event-driven architectures, cloud-native platforms on AWS and multi-tenant SaaS.

I currently lead a team of engineers at **[Digio](https://www.digio.in)**. We build the back-end services behind eSign, Digi-Docs, Forms and KYC.

---

## 🚀 What I'm working on

- **[Ampairs](https://github.com/omprakashsrv/ampairs)** *(personal project, source-available, 2025 – present)*: a multi-tenant business management platform with CRM, inventory, orders, invoicing and payments.
  - Spring Boot 4 / Java 21 / Kotlin modular monolith with 25 domain modules, workspace-based multi-tenancy, device-aware JWT auth and Flyway migrations
  - Event-driven integration with Kafka (dead-letter queues, automatic fallback to an in-memory broker), plus Testcontainers integration tests, Ansible provisioning and GitHub Actions CI/CD
  - Spec-driven, AI-native development workflow (Spec Kit, CLAUDE.md / AGENTS.md), plus an on-device AI assistant module with text-to-SQL
  - Back-end: [`ampairs`](https://github.com/omprakashsrv/ampairs) (Spring Boot + Kotlin)
  - Mobile/Desktop: [`ampairs-app`](https://github.com/omprakashsrv/ampairs-app) (Kotlin Multiplatform + Compose Multiplatform, offline-first)
  - Web: [`ampairs-web`](https://github.com/omprakashsrv/ampairs-web) (Angular + Material 3)

## 🏗️ Highlights

- **DigiVault**: a zero-knowledge PII vault. It uses AES-256-GCM envelope encryption and crypto-shredding for DPDP Act compliance, and ships as a modular SDK for near drop-in adoption.
- **Centralized batch processing platform** for KYC, Payments, eSign and Mandates. It runs on a reactive stack (WebFlux, R2DBC) with a plugin-based execution engine and distributed job scheduling. Bulk processing has had zero production failures.
- **AI-powered PDF summarization** with Server-Sent Events, scalable processing pipelines and intelligent caching.
- **Adaptive concurrency control** with dynamic throttling and proactive alerting. It prevents outages during peak traffic.
- Led the **migration from a monolith to modular microservices**.
- Improved the success rate of Aadhaar-based eSign to **10% above industry benchmarks**.
- Built a **Distribution Management System** and offline-first Android apps for field sales, delivery and retail. Integrated ESC/POS printers, barcode scanners and weighing scales.

## 📊 By the numbers

- 12+ back-end services · 8+ mobile apps · 5+ web apps · 2+ platform modernizations
- 100+ RESTful APIs and microservices
- 80% improvement in application performance
- 99.99% system availability
- 90% of build/test/deploy automated with CI/CD

## 🛠️ Tech stack

**Languages:** Java · Kotlin · Go · JavaScript · TypeScript
**Frameworks:** Spring Boot · Kotlin Multiplatform · Compose Multiplatform · Angular · Hibernate · JavaFX · Flutter · Node.js
**Mobile:** Android SDK · MediaPipe · Firebase
**Cloud & DevOps:** AWS · S3 · Docker · CI/CD
**Databases:** PostgreSQL · MySQL · MongoDB
**Big Data:** Apache Spark · Hadoop · Iceberg
**APIs:** REST · GraphQL · Server-Sent Events
**Devices:** Bluetooth · USB · ESC/POS printers · serial communication · weighing scales

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)

## 💼 Experience

### Tech Lead / Software Engineer · [Digio.in](https://www.digio.in), Bengaluru
*September 2021 – Present*

**Key result areas**
- Lead the design, development and architecture of highly scalable back-end services for the eSign, Digi-Docs, Forms and KYC platforms. Lead a team of 5 engineers.
- Define technology roadmaps: evaluate technologies, frameworks and architectural patterns, and align technical direction with business goals and long-term product strategy.
- Lead solution architecture, technical design reviews, architecture governance, code reviews and production releases.
- Set engineering governance, coding standards, architectural guidelines and development best practices across engineering teams.
- Work with product management, business stakeholders and cross-functional teams to turn business requirements into robust technical solutions.
- Design enterprise integration strategies with REST APIs, messaging platforms and event-driven architectures.
- Run system capacity planning, performance assessments and scalability analysis for mission-critical applications.
- Improve performance and production reliability by fixing bottlenecks, memory leaks, thread contention and database connection issues, and by adding cross-platform caching across back-end, web and Android.
- Standardize user interfaces through a shared design system across customer-facing apps and internal platforms.

**Highlights**
- Built a **centralized batch processing platform** for KYC, Payments, eSign and Mandates. It uses a reactive architecture (WebFlux, R2DBC), a plugin-based execution engine and distributed job scheduling. Resilient job recovery and adaptive concurrency gave zero production failures in bulk processing and report generation.
- Architected and built **DigiVault**, a zero-knowledge PII vault with AES-256-GCM envelope encryption and crypto-shredding for DPDP Act compliance. It removed plaintext PII from databases. Its modular SDK (JPA/Hibernate, MongoDB, multi-transport) allows near drop-in enterprise adoption.
- Built an **AI-powered PDF summarization platform** using Server-Sent Events, scalable processing pipelines and intelligent caching for real-time document analysis.
- Designed **adaptive concurrency control** with dynamic throttling, real-time monitoring and proactive alerting. It prevented production outages during peak traffic.
- Led the **migration from a legacy monolith to modular microservices**, which improved scalability, deployment agility and maintainability.
- Designed and developed an in-house **PDF editing and digital document signing platform** (Angular, Go, Spring Boot).
- Built a **secure multi-tenant document storage platform** with ACL-based authorization and domain-level security controls.
- Re-architected the **Android SDK** into a modular framework for better extensibility and maintainability.
- Developed **real-time selfie capture and face matching** with MediaPipe and Firebase for digital identity verification.
- Owned the **enterprise billing platform** that bills for all Digio products.
- Raised the success rate of **Aadhaar-based eSign** to 10% above industry benchmarks.
- Started and led a **stock-market transaction monitoring platform** to improve analytics and operational efficiency.

### Tech Lead / Software Engineer · Recibo Technologies, Bengaluru
*July 2015 – August 2021*

- Architected and developed a scalable **Distribution Management System (DMS)** for retailers, wholesalers and brands.
- Built end-to-end business modules: customer management, product catalog, pricing, inventory, invoicing, payments, order processing and sales force automation.
- Developed **offline-first Android apps** for field sales, delivery, inventory management and retailer ordering.
- Delivered enterprise web, desktop and mobile solutions for wholesale and distribution businesses across India.
- Built **JavaFX-based ERP software** for warehouse management, GST-compliant billing, inventory control and invoicing.
- Integrated **Bluetooth and USB ESC/POS printers** into Android and desktop apps for receipt printing.
- Developed a **Cable TV billing and recurring payment platform** with automated notifications, complaint management and collections tracking.
- Designed a mobile workflow for field collection agents covering dues management and operational reporting.
- Led solution architecture across back-end, web, desktop and mobile, and mentored engineering teams.

### Associate Software Developer · Softserve Global, Bengaluru
*January 2015 – June 2015*

- Developed offline-first Android apps (**Merchant@Hand** and **Store@Hand**) for retail operations.
- Built core business modules: customer management, product catalog, pricing, inventory, invoicing and payments.
- Integrated Bluetooth and USB thermal printers, barcode scanners, barcode printers and digital weighing scales for end-to-end retail automation.

## 🧭 Core competencies

Back-end development · Microservices architecture · Cloud engineering · RESTful API development · Technical project management · Agile / Scrum · Android platform development · Cross-platform development · Performance optimization · CI/CD · Technical documentation · Requirement gathering & analysis · Root cause analysis · User experience design

## 🎓 Education

**B.Tech, Computer Science**, National Institute of Technology, Srinagar (2014)

---

💬 Ask me about **back-end architecture, multi-tenant SaaS, offline-first sync, Kotlin Multiplatform, or FinTech/KYC/eSign systems**.
