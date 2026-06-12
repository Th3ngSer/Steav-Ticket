# 🚌 Steav-Ticket | Modern Bus Booking System

![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=for-the-badge&logo=nestjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

**Steav-Ticket** is a robust, full-stack web application designed for seamless bus ticket booking and passenger management. It provides an intuitive interface for travelers to book seats and a secure, powerful dashboard for administrators to manage daily transit operations.

---

## ✨ Features

### 👤 For Passengers (Users)
* **Smart Search:** Find bus schedules by origin, destination, and travel date.
* **Interactive Seat Selection:** Visually select available seats using a dynamic layout.
* **Secure Checkout:** Simulated payment process supporting Cash, Card, and ABA.
* **Booking Management:** View active tickets, past trips, and manage user profiles.

### 🛡️ For Administrators
* **Fleet Management:** Add, update, and monitor the bus fleet and capacity.
* **Route & Schedule Control:** Define travel routes, departure times, and ticket pricing.
* **Live Passenger Manifest:** Track real-time bookings, assigned seats, and payment statuses.
* **Role-Based Security:** Advanced NestJS Guards ensure only authorized admins can access the dashboard.

---

## 💻 Tech Stack

### Frontend
* **Framework:** Vue 3 (Composition API)
* **Tooling:** Vite
* **Language:** TypeScript
* **Styling:** Custom CSS / HTML5

### Backend
* **Framework:** NestJS
* **Language:** TypeScript
* **Database:** MongoDB (with Mongoose ORM)
* **Authentication:** JSON Web Tokens (JWT) & bcrypt
* **Validation:** class-validator & class-transformer

---

## 🚀 Getting Started

Follow these instructions to set up the project locally for development and testing.

### Prerequisites
* **Node.js** (v18 or higher recommended)
* **MongoDB** (Running locally on default port `27017`)
* **Git**

### 1. Clone the Repository
```bash
git clone [https://github.com/AhMeow0/Steav-Ticket.git](https://github.com/AhMeow0/Steav-Ticket.git)
cd Steav-Ticket
