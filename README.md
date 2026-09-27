# Azure SQL Hackathon Demo

A full-stack web application demonstrating secure user authentication, Azure SQL database integration, and a responsive dashboard.

## 🚀 Features

* User Login
* Create Account
* Secure password hashing
* JWT authentication
* Azure SQL Database integration
* Responsive dashboard
* Application records
* Azure SQL connection status
* Failover simulation
* Security and architecture visualization

## 🛠️ Technologies Used

* HTML
* CSS
* JavaScript
* Node.js
* Express.js
* Microsoft Azure SQL
* JWT
* bcrypt

## 📁 Project Structure

```text
project/
├── backend/
│   └── schema.sql
├── public/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── css/
│   └── js/
├── server.js
├── package.json
├── .env.example
└── README.md
```

## ▶️ Run Locally

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd YOUR_PROJECT_FOLDER
```

Install dependencies:

```bash
npm install
```

Create a `.env` file from `.env.example` and configure your database settings.

Start the application:

```bash
npm start
```

Open:

```text
http://localhost:5000
```

## ☁️ Azure SQL

The application is designed to connect to Microsoft Azure SQL Database.

Configure the required Azure SQL connection information in the `.env` file.

**Do not commit `.env` to GitHub.**

## 🔐 Security

* Passwords are hashed using bcrypt.
* Authentication uses JWT.
* Database credentials are stored in environment variables.
* Sensitive credentials are not exposed in the frontend.

## 🎯 Hackathon Demo

The application demonstrates:

**Frontend → Backend API → Azure SQL Database**

It also includes a dashboard for demonstrating database connectivity, application records, and failover concepts.

## 👥 Team

Developed as a hackathon project.
