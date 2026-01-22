---
layout: page
title: Projects
subtitle: Engineering & Technical Portfolio
---

Here are some of what I've been working lately.

### 💳 [Idempotent Payment Gateway](https://github.com/zgabrieloliveira/idempotent-payment-gateway)
Resilient financial API designed to handle network failures and retries.
- **Tech:** Redis, Idempotency Keys, Atomic Locking.
- **Highlight:** Guarantees transactions are never duplicated, maintaining consistency even with client retries.

---

### 📡 [Event-Driven Webhook Dispatcher](https://github.com/zgabrieloliveira/event-driven-webhook-dispatcher)
Fault-tolerant webhook delivery pipeline utilizing Event-Driven Architecture.
- **Tech:** Apache Kafka, Resilience4j (Circuit Breaker & Retry), Docker.
- **Highlight:** Ensures eventual delivery and system stability even during third-party service outages.

---

### 🎟️ [Real-Time Concurrency Booking](https://github.com/zgabrieloliveira/realtime-concurrency-booking)
High-performance booking system engineered to eliminate *Race Conditions*.
- **Tech:** .NET 8, Redis Distributed Locks, Docker.
- **Highlight:** Validated via stress testing (50 req/s) ensuring 0% overbooking.

---

### 🏢 [SaaS Multi-tenancy Architecture](https://github.com/zgabrieloliveira/saas-multitenant)
Secure data isolation architecture for multi-tenant applications.
- **Tech:** .NET 9, EF Core Global Filters.
- **Highlight:** Implemented database-level security (logical Row Level Security) to prevent data leakage.
