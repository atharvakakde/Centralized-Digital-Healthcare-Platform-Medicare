# Centralized Digital Healthcare Platform

A comprehensive healthcare management system designed to digitize and streamline healthcare operations. The platform enables efficient patient management, appointment scheduling, electronic medical record handling, and healthcare service administration through a secure and user-friendly web application.

---

## Project Overview

The Centralized Digital Healthcare Platform aims to bridge the gap between patients and healthcare providers by providing a unified digital ecosystem for healthcare management.

The system helps hospitals, clinics, doctors, and patients manage healthcare services efficiently while ensuring data security, accessibility, and scalability.

---

## Features

### Patient Management

* Patient Registration
* Patient Profile Management
* Patient Search and Records
* Medical History Tracking

### Appointment Scheduling

* Book Appointments
* Manage Appointment Slots
* Appointment Status Tracking
* Schedule Management

### Electronic Medical Records (EMR)

* Digital Patient Records
* Medical History Storage
* Diagnosis Information
* Treatment Records Management

### Healthcare Service Management

* Healthcare Service Listings
* Service Information Management
* Department Management

### Authentication and Authorization

* Secure Login and Registration
* JWT-Based Authentication
* Role-Based Access Control (RBAC)
* Protected Routes

### Responsive User Interface

* Mobile-Friendly Design
* Modern Dashboard
* Intuitive User Experience

---

## Technology Stack

### Frontend

* React.js
* JavaScript (ES6+)
* Tailwind CSS
* HTML5
* CSS3

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose ODM

### Authentication

* JSON Web Token (JWT)
* bcrypt.js

### APIs

* RESTful APIs

### Development Tools

* Git
* GitHub
* Visual Studio Code

---

## System Architecture

```text
Frontend (React.js)
        |
        v
REST API Layer
        |
        v
Backend (Node.js + Express.js)
        |
        v
MongoDB Database
```

---

## Installation and Setup

### Prerequisites

* Node.js
* MongoDB
* Git

### Clone the Repository

```bash
git clone https://github.com/yourusername/Centralized-Digital-Healthcare-Platform.git

cd Centralized-Digital-Healthcare-Platform
```

### Install Dependencies

```bash
npm install
```

### Configure Environment Variables

Create a `.env` file in the root directory:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_secret_key
```

### Run the Application

```bash
npm run dev
```

### Application URLs

Frontend:

```text
http://localhost:5173
```

Backend:

```text
http://localhost:5000
```

---

## Project Modules

### Patient Management

Manage patient profiles, records, and healthcare history.

### Appointment Scheduling

Handle appointment booking, cancellation, and scheduling.

### Medical Records

Store and retrieve patient medical records securely.

### Authentication and Authorization

Manage users, permissions, and access control.

### Healthcare Services

Provide healthcare-related services and information.

---

## Security Features

* JWT Authentication
* Password Encryption using bcrypt
* Protected API Routes
* Role-Based Access Control
* Secure Data Management

---

## Future Enhancements

* AI-Powered Health Recommendations
* Online Doctor Consultation
* E-Prescription Management
* Health Analytics Dashboard
* Multi-Hospital Integration
* Real-Time Notifications
* Telemedicine Support
* Cloud-Based Deployment

---

## Learning Outcomes

This project demonstrates practical implementation of:

* Full Stack Web Development
* REST API Development
* Authentication and Authorization
* Database Design and Management
* Healthcare Information Systems
* Responsive UI Development
* Secure Data Handling

---

## Author

Atharva Dhanraj Kakde

B.Tech Computer Science and Engineering
Minor in Artificial Intelligence and Machine Learning (AI/ML)
Jawaharlal Nehru Engineering College (JNEC), MGM University

GitHub: https://github.com/atharvakakde

Portfolio: https://atharva-kakde-portfolio.vercel.app

