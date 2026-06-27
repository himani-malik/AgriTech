# 🌾 AgriTech – Smart Agriculture Intelligence Platform

> A data-driven agriculture analytics platform that enables users to explore crop production trends, compare states, analyze agricultural performance, and gain insights through an intelligent dashboard.

---

## 📌 Overview

AgriTech is a full-stack web application designed to make agricultural data easy to understand and analyze. The platform provides interactive visualizations, state-wise comparisons, crop analysis, and AI-assisted insights to help users explore agricultural trends across India.

This project aims to support students, researchers, policymakers, and agriculture enthusiasts in making data-driven decisions.

---

## ✨ Key Features

### 📊 Interactive Dashboard
- View national agricultural statistics at a glance.
- Identify top-performing states.
- Analyze yearly production trends.
- Visualize insights through dynamic charts.

### 🗺️ State Analysis
- Compare multiple states side-by-side.
- Evaluate crop production, cultivated area, and yield performance.

### 🌱 Crop Analysis
- Explore production trends for individual crops.
- Analyze crop performance across different states and years.
- Gain detailed insights through visual reports.

### 🤖 Agro AI Assistant
- Natural language-based query system.
- Ask agriculture-related questions and receive instant insights.
- Quick action prompts for faster exploration.

### 🔐 Secure Authentication
- User Registration and Login.
- Passwords securely hashed using Node.js crypto module.
- User data stored securely.

---

## 🛠️ Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Node.js, Express.js |
| Database | PostgreSQL |
| Data Visualization | Chart.js |
| Authentication | Node.js Crypto |
| Configuration | Dotenv |

---

## 🏗️ System Architecture

```text
User
  ↓
Frontend (HTML/CSS/JS)
  ↓
Express.js Server
  ↓
REST APIs
  ↓
PostgreSQL Database
```

---

## 📂 Project Structure

```text
Agritech-main/
├── backend/
├── public/
├── agritech.sql
├── package.json
├── .env
└── README.md
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-username/Agritech.git
cd Agritech
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file:

```env
DB_USER=your_database_username
DB_PASSWORD=your_database_password
DB_HOST=localhost
DB_PORT=5432
DB_NAME=agritech
PORT=5000
```

### Run the Application

```bash
npm start
```

Open:

```text
http://localhost:5000
```

---

## 📈 Future Enhancements

- Weather Forecast Integration
- AI-based Crop Recommendations
- Satellite Data Integration
- District-Level Analytics
- Cloud Deployment

---

## 🎯 Learning Outcomes

- Full Stack Web Development
- REST API Development
- Database Integration
- Authentication & Security
- Data Visualization
- Agricultural Data Analytics

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Himani Malik**

Passionate about leveraging technology and AI to solve impactful real-world solutions.

⭐ If you found this project useful, consider giving it a star!
