# Coaching Platform

A full-stack web platform that connects coaches with people who want to expand their knowledge through accessible and affordable courses.

The application allows users to discover coaches, enroll in courses, interact with the platform in real time, and manage payments securely.

---

# Features

- User authentication and authorization
- Course discovery and enrollment
- Coach profiles and course management
- Secure payment processing
- Real-time interactions
- Location-based features for discovering services

---

# Tech Stack

## Frontend
- HTML
- CSS
- JavaScript
- React
- ReactDOM

The frontend is built as a **Single Page Application (SPA)** using React, providing a dynamic and responsive user experience.

## Backend
- Python
- Flask
- REST API architecture

The backend handles application logic, authentication, database interactions, and communication with external services.

## Database
- PostgreSQL
- SQLAlchemy (ORM)

Data models are managed using SQLAlchemy, enabling structured interaction with the relational database.

---

# Authentication

Authentication and authorization are implemented using **JSON Web Tokens (JWT)**, ensuring secure session handling and protected routes.

---

# External Services

The platform integrates several third-party services:

- **Google Maps API** for location-based features
- **Stripe** for secure payment processing
- **Socket.IO** for real-time communication

---

# Project Architecture

The application follows a **client–server architecture**, separating the frontend and backend into independent services.
Frontend (React SPA)
|
| REST API
|
| Backend (Flask)
|
| ORM
|
| PostgreSQL Database

This structure improves scalability, maintainability, and modular development.

---

# Version Control

The project uses **Git** for version control and is hosted on **GitHub** for collaboration and source management.

---

# Future Improvements

- Course recommendation system
- Advanced search and filtering
- Messaging system between users and coaches
- Improved analytics for course creators
- Deployment with Docker and cloud infrastructure

---

# Author

**Cristian Trapiello**  
Full-Stack Developer focused on **React, Python (Flask), and REST API development**.  

📧 Contact: mader.projects@gmail.com
