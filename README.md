# GearHub – Final Degree Project

## 🚘 Overview
**GearHub** is a full-stack social network platform designed for users and auto workshops. It enables users to manage their vehicles, live-messaging between users and workshops, track maintenance history, and participate in forum discussions. Workshops can manage services, respond to inquiries, and enhance visibility. Users can review workshops and add vehicles to their profiles. Cocreated with [José María García Sánchez](https://github.com/Terion0)

Developed as a final project for the Higher technician in Multi-platform Applications development.

---

## 🧩 Architecture
GearHub uses a **microservice-based architecture** deployed with Docker and orchestrated using Docker Compose. Could be improved by using kubernetes or Docker Swarm orchestrator.

**Main components:**
- 6 ASP.NET Core microservices
- PostgreSQL and MongoDB databases
- Ocelot API Gateway
- Web frontend (React + TailwindCSS)
- Android mobile app (Jetpack Compose + Hilt)

---

## 🔗 Repositories
| Module | Description | Repo Link |
|--------|-------------|-----------|
| Auth Service | Handles JWT, user registration, email verification | [🔗](https://github.com/Terion0/AuthApi_) |
| Profiles Service | User profiles, followers, images | [🔗](https://github.com/Terion0/ProfApi) |
| Workshops Service | Vehicle, workshop, orders, invoices | [🔗](https://github.com/rasitoo/WebApiTaller) |
| Reviews Service | Reviews and workshop replies | [🔗](https://github.com/Terion0/RevApi) |
| Communities Service | Forums, threads, roles, likes | [🔗](https://github.com/Terion0/ComunApi) |
| Messaging Service | Real-time messaging with SignalR | [🔗](https://github.com/rasitoo/WebApiMessages) |
| API Gateway | Unified API routing with Ocelot | [🔗](https://github.com/rasitoo/WebApiGateway) |
| Web Frontend | React + TailwindCSS + SignalR frontend | [🔗](https://github.com/Terion0/gearhub) |
| Mobile App | Android app with Jetpack Compose | [🔗](https://github.com/rasitoo/GearHubMobile) |

---

## 🛠️ Tech Stack
**Backend:** ASP.NET Core, SignalR, Ocelot, PostgreSQL, MongoDB, Docker  
**Frontend Web:** React, TailwindCSS, Nginx  
**Frontend Mobile:** Jetpack Compose, Kotlin, Hilt, Retrofit, DataStore, SignalR  
**DevOps:** Docker Compose, Docker Hub

---

## 🚀 Features
- User registration, authentication, and secure login via JWT
- Vehicle registration and maintenance tracking
- Workshop profiles and service management
- Real-time private messaging between users and workshops
- Forum system with roles, threads, and replies
- Review and rating system for workshops
- Intelligent recommendations (future improvement)
- Fully containerized and deployable

---
<!--
## 📲 Screenshots
- Mobile App (Jetpack Compose)
- Web Interface (React + Tailwind)
- Forum and Messaging modules

---
-->
## ⚙️ Deployment
The full system can be deployed using `docker-compose`:
```bash
git clone https://github.com/rasitoo/TFG-social_network_GEARHUB.git
cd TFG-social_network_GEARHUB
docker-compose up --build
```
All services, including the gateway, databases, and web frontend will be launched automatically. Android apk can be downloaded from [Google Drive](https://drive.google.com/drive/folders/1YMc2tlJxLj-K0ueN4pxn_d_T2q4AK4QY?usp=drive_link)

---

## 👨‍💻 Authors
- Rodrigo Tapiador Cano ([GitHub](https://github.com/rasitoo) · [LinkedIn](https://www.linkedin.com/in/rodrigo-tapiador-cano-162723258/))
- José María García Sánchez ([GitHub](https://github.com/Terion0) · [LinkedIn](https://www.linkedin.com/in/jos%C3%A9-mar%C3%ADa-garc%C3%ADa-s%C3%A1nchez-13236b176/))

---

## 📄 License
This project is open-source under the MIT License.
