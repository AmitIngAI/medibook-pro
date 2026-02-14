# 🏥 MediBook-Pro

> Full-stack healthcare appointment booking system with secure authentication, role-based access control, and payment integration.

![Java](https://img.shields.io/badge/Java-17-orange?style=for-the-badge&logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-green?style=for-the-badge&logo=springboot)
![React](https://img.shields.io/badge/React-18-blue?style=for-the-badge&logo=react)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue?style=for-the-badge&logo=mysql)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

## 🌟 Overview

MediBook-Pro is a comprehensive healthcare platform that connects patients with doctors, enabling seamless appointment booking, management, and secure payment processing.

## ✨ Features

### 👤 Patient Portal
- 🔐 Secure registration & JWT-based authentication
- 🔍 Search doctors by specialization, location, availability
- 📅 Real-time appointment booking with slot selection
- 💳 Integrated payment gateway (Razorpay/Stripe)
- 📧 Email/SMS appointment confirmations
- 📊 Personal dashboard with appointment history

### 👨‍⚕️ Doctor Portal
- ✅ Manage incoming appointment requests
- 🕒 Set availability schedules
- 👥 View patient details and history
- 📈 Analytics and earnings dashboard

### 🔧 Admin Panel
- 👨‍⚕️ Doctor verification and approval system
- 📊 Platform-wide analytics and reports
- 👥 User management (patients, doctors)
- ⚙️ System configuration

## 🛠️ Tech Stack

### Backend
| Technology | Purpose |
|------------|---------|
| Spring Boot 3.x | REST API Framework |
| Spring Security | Authentication & Authorization |
| JWT | Token-based Authentication |
| MySQL 8.0 | Primary Database |
| Redis | Caching & Sessions |
| Hibernate/JPA | ORM |
| AWS S3 | File Storage |
| Razorpay/Stripe | Payment Processing |

### Frontend
| Technology | Purpose |
|------------|---------|
| React 18 | UI Library |
| Material-UI 5 | Component Library |
| React Router 6 | Navigation |
| Axios | HTTP Client |
| Context API | State Management |

## 🚀 Quick Start

### Prerequisites
- Java 17+
- Node.js 16+
- MySQL 8.0+
- Maven 3.8+

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/AmitIngAI/medibook-pro.git
cd medibook-pro

2...Backend Setup
cd backend
# Copy and configure environment
cp src/main/resources/application.properties.example src/main/resources/application.properties
# Edit application.properties with your database credentials
# Run backend
mvn clean install
mvn spring-boot:run

3...Frontend Setup
cd frontend

# Copy and configure environment
cp .env.example .env
# Edit .env with your API URL
# Install dependencies and run
npm install
npm start

4..Access the application
Frontend: http://localhost:3000
Backend API: http://localhost:8080/api
API Health Check: http://localhost:8080/api/health





