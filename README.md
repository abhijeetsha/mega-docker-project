# Docker-with-CIcd-pipeline
## MEGA PROJECT: Dockerized Microservices Platform (Production-Grade)
### 🧠 Project Overview
## 📌 Application
### E-Commerce Microservices Platform
## 📦 Services
| Service                 | Tech              |
| ----------------------- | ----------------- |
| Frontend                | React + Nginx     |
| User Service            | Node.js + Express |
| Product Service         | Node.js           |
| Order Service           | Node.js           |
| Database                | MySQL             |
| Cache                   | Redis             |
| Reverse Proxy           | Nginx             |
| CI/CD                   | Jenkins           |
| Container Orchestration | Docker Compose    |

## 🏗️ Architecture
* Client
*   |
*   v
* Nginx (Reverse Proxy)
*   |
* ------------------------------------------------
* |        |             |              |
* User API | Product API | Order API | Redis
*    |           |             |
*    -----------------------------
*               |
*             MySQL

## Project Structure
* mega-docker-project/
* │
* ├── frontend/
* │   ├── Dockerfile
* │   └── build/
* │
* ├── services/
* │   ├── user-service/
* │   ├── product-service/
* │   └── order-service/
* │
* ├── nginx/
* │   └── nginx.conf
* │
* ├── mysql/
* │   └── init.sql
* │
* ├── redis/
* │
* ├── docker-compose.yml
* └── Jenkinsfile
