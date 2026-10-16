# Homework-1
# Smart Park Engine (SPE) Platform

A comprehensive software requirements and project management repository for a real-time smart parking management solution. The SPE platform bridges mobile and web client interfaces with cloud-hosted microservices, automated license plate recognition (LPR) hardware, and secure payment processing.

---

## Key Features
* **Real-Time Occupancy Tracking:** Live websocket synchronization updating parking space availability and pricing maps with under 500ms latency.
* **Smart Reservations & Digital Payments:** Seamless spot booking with automated 5-minute temporary holds and secure tokenized payment processing via Stripe.
* **Advanced Gate Controls & LPR Interfacing:** Integrated automated license plate recognition for frictionless entry/exit bypass, supplemented by operator manual gate override consoles (`UC-18`) for exception handling.
* **Comprehensive Reporting Dashboards:** Administrative tools providing operators and municipal stakeholders with occupancy heat maps, turnover metrics, and audit log exports.

---

## Project Parameters & Financial Baseline
* **Lifecycle Duration:** 11 Weeks (3 Months) across structured Agile Scrum sprints.
* **Total Labor Allocation:** 800 Engineering & Management Hours.
* **Approved Baseline Budget:** $38,830 (inclusive of labor, AWS cloud infrastructure, third-party tooling, and a 10% contingency reserve).
* **Risk Threshold Cap:** $45,890 (30% maximum overbudget ceiling).

---

## Core Project Team
* **Project Manager:** Alexa Rivera
* **Lead Developer:** Marcela Villegas
* **UI/UX & Frontend Developer:** Sofia Chen
* **QA / Tester:** Guillermo Martin
* **DevOps Engineer:** Giselle Denisse

---

## Repository Structure
* `/docs` — Contains the complete Software Requirements Specification (SRS), Work Breakdown Structure (WBS), Schedule Matrix, and Risk Register.
* `/assets` — Architecture diagrams, WBS trees, and Trello sprint board configurations.

---

## Tech Stack & Standards
* **Frontend:** Cross-platform mobile (iOS/Android) and responsive web portal utilizing embedded mapping SDKs (Mapbox/Google Maps).
* **Backend & Database:** RESTful APIs, WebSockets, relational database schemas, and AES-256 / TLS 1.3 encryption protocols.
* **Methodology:** Agile Scrum framework with bi-weekly sprint iterations and strict adherence to WCAG 2.1 AA and ISO 27001 standards.
