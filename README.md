# 🌱 Gratitude Garden – Couples

> A digital garden where couples grow their relationship through gratitude, memories, and meaningful moments.
> 
<p align="center">
<img width="1584" height="396" alt="Linkedin_coverphoto" src="https://github.com/user-attachments/assets/4c08ff4b-9011-44db-8a4b-bf91e362ddcf" alt="Gratitude Garden – Couples" width="100%"/>
</p>


<p align="center">
  Android • iOS • Kotlin Multiplatform • Spring Boot • PostgreSQL
</p>

---

# 1. 📱 App Overview

**Gratitude Garden – Couples** is a mobile application designed to help couples build a habit of appreciation by turning every gratitude into a beautiful plant in their shared garden.

Each gratitude creates a new plant, allowing couples to visually see their relationship garden grow over time.

## 🎨 UI/UX Preview

### App Mockups

<!-- Replace these image paths with your actual screenshots -->

<p align="center">
  <img width="360" height="800" alt="ChatGPT Image Aug 3, 2026, 05_35_35 PM" src="https://github.com/user-attachments/assets/414a94c9-0cf4-49a5-8239-a316835c83b7" width="250"/>

</p>



> More UI/UX screens and design details will be added to the documentation.

## ✨ MVP Features

### 🌸 Plant a Flower for Gratitude
Turn a simple expression of gratitude into a plant that becomes part of the couple's shared garden.

### 🌿 Couple Garden
View and explore a shared garden that represents the gratitude and positive moments accumulated by both partners.

### 💌 Invite Your Partner
Invite your partner and create a shared couple space where both partners can contribute to the garden.

### 📝 Gratitude & Memories
Create gratitude entries and attach a **memory and image** to preserve meaningful moments and experiences.

### 🕐 Gratitude Timeline
Browse previous gratitude entries through a timeline, making it easy to revisit special moments and memories.

### 🔔 Real-Time Partner Notifications
Notify your partner when a new gratitude plant is created, helping them stay connected with new moments of appreciation.

### 🌱 Rare & Legendary Plants
Discover special **Rare** and **Legendary** plants through the subscription experience and make your shared garden more unique.

### 💳 Subscription
Subscription functionality provides access to premium features and exclusive plants.

---

# 2. 🛠️ Engineering & Technical Implementation

I designed and developed the project across the **UI/UX, database, backend, mobile applications, software engineering, and DevOps infrastructure**.

## 🎨 UI/UX Design

- Designed the complete application experience and user flows in **Figma**.
- Created UI/UX concepts for the couple garden, gratitude creation, timeline, memories, notifications, and subscription flows.
- Designed the visual system around the concept of growing a shared gratitude garden.
- Created responsive and consistent designs for the mobile experience.

**Tool:** Figma

---

## 🗄️ Database Design & Implementation

Designed and implemented the application's database using **PostgreSQL**.

Responsibilities included:

- Database architecture and relational data modeling.
- Designing relationships between users, couples, gratitudes, plants, memories, subscriptions, and notifications.
- Implementing database constraints and data integrity rules.
- Creating indexes and optimizing database queries.
- Structuring the database to support future scalability and additional features.

**Database:** PostgreSQL

---

## ⚙️ Backend Engineering

Designed and implemented the backend using **Java & Spring Boot**.

Responsibilities included:

- Designing the backend architecture and service structure.
- Developing RESTful APIs for mobile applications.
- Implementing user and couple management.
- Building partner invitation workflows.
- Implementing gratitude and plant creation logic.
- Managing gratitude memories and images.
- Implementing gratitude timeline functionality.
- Developing subscription and premium feature logic.
- Implementing Rare and Legendary plant functionality.
- Building real-time notification functionality for partner activities.
- Implementing authentication, authorization, validation, and error handling.
- Designing APIs with maintainability, scalability, and reliability in mind.

**Backend:** Java, Spring Boot  
**Database:** PostgreSQL

---

## 📱 Mobile Application – Android & iOS

The mobile application was developed using **Kotlin Multiplatform (KMP)** to share code across Android and iOS while providing a native mobile experience.

Responsibilities included:

- Developing the Android and iOS applications using **Kotlin Multiplatform**.
- Integrating mobile applications with the Spring Boot backend APIs.
- Implementing authentication and user flows.
- Building couple invitation and connection flows.
- Implementing gratitude creation and plant generation.
- Building the couple garden experience.
- Implementing gratitude timeline and memory features.
- Integrating image handling and notifications.
- Implementing subscription-related mobile flows.
- Maintaining a shared and scalable codebase for Android and iOS.

**Mobile:** Kotlin Multiplatform (KMP)  
**Platforms:** Android & iOS

---

## ☁️ Software Engineering & DevOps

In addition to application development, I worked across the software engineering lifecycle, including backend infrastructure and deployment.

Responsibilities included:

- Designing the overall application architecture.
- Managing development environments and application configuration.
- Setting up and maintaining backend/server infrastructure.
- Deploying and maintaining backend services.
- Managing database deployment and configuration.
- Implementing environment-specific configuration for development and production.
- Monitoring application health and backend reliability.
- Applying software engineering practices focused on maintainability, scalability, security, and reliability.
- Managing the development workflow from UI/UX and database design through backend implementation, mobile integration, deployment, and maintenance.

---

## 🧩 Technology Stack

| Area | Technology |
|---|---|
| **Mobile** | Kotlin Multiplatform (KMP) |
| **Android** | Kotlin |
| **iOS** | Kotlin Multiplatform / iOS |
| **Backend** | Java, Spring Boot |
| **Database** | PostgreSQL |
| **UI/UX** | Figma |
| **API** | RESTful APIs |
| **Architecture** | Modular / Layered Backend Architecture |
| **Real-Time** | Real-Time Notification System |
| **DevOps** | Server & Backend Deployment |

---

## 🏗️ High-Level Architecture

```text
                    ┌─────────────────────┐
                    │      Figma UI/UX    │
                    └──────────┬──────────┘
                               │
                               ▼
              ┌────────────────────────────────┐
              │       Mobile Applications      │
              │                                │
              │   Android + iOS (KMP)          │
              └───────────────┬────────────────┘
                              │
                         REST APIs
                              │
                              ▼
              ┌────────────────────────────────┐
              │       Java / Spring Boot       │
              │                                │
              │  Authentication                │
              │  Couple Management             │
              │  Gratitude & Plants            │
              │  Memories                       │
              │  Subscriptions                  │
              │  Notifications                  │
              └───────────────┬────────────────┘
                              │
                              ▼
                    ┌──────────────────┐
                    │    PostgreSQL    │
                    │                  │
                    │ Users            │
                    │ Couples          │
                    │ Gratitudes       │
                    │ Plants           │
                    │ Memories         │
                    │ Subscriptions    │
                    │ Notifications    │
                    └──────────────────┘
```

---

## 👨‍💻 My Role

I worked across the complete product development lifecycle, taking responsibility for:

- **UI/UX Design** – Product flows and mobile interface design in Figma.
- **Database Engineering** – PostgreSQL database architecture, schema design, implementation, and optimization.
- **Backend Engineering** – Java/Spring Boot architecture, APIs, business logic, authentication, subscriptions, and notifications.
- **Mobile Development** – Android and iOS applications using Kotlin Multiplatform.
- **Software Engineering** – Application architecture, code organization, testing, maintainability, and scalability.
- **DevOps & Infrastructure** – Server setup, deployment, configuration, and backend infrastructure management.

---

## 🚀 Project Status

**Gratitude Garden – Couples** is currently being developed with the MVP focused on creating a shared, engaging, and meaningful gratitude experience for couples.

More documentation, screenshots, architecture diagrams, and technical details will be added as the project evolves.

---

<p align="center">
  🌱 <strong>Grow gratitude. Grow together.</strong> 💕
</p>
