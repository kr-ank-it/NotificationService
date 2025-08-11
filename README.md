# Notification Service

A microservice responsible for sending email notifications triggered by events in the system.  
Designed for **asynchronous communication** using **Kafka** to ensure scalable and reliable notification delivery.

---

## 🚀 Features
- **Event-driven architecture** — consumes messages from Kafka topics.
- **Supports multiple channels** — email (extensible).
- **Configurable templates** for different notification types.
- **Retry mechanism** for failed notifications.
- **Loosely coupled** — can be integrated with any service publishing events.

---

## 🛠 Tech Stack
- **Language:** Java (Spring Boot)
- **Messaging:** Apache Kafka
- **Email Service:** SMTP

---

