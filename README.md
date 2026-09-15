# MMS3 Group Project

📌 Project Overview

This repository contains three software systems developed as part of the MMS3 NIIT Group Project.

The project consists of:

- GadgetHub – Online Gadget & Accessories E-Commerce Platform
- CampusConnect – Student Academic & Course Management System
- MediCare – Hospital Appointment & Patient Management System

The goal of the project is to develop practical full-stack applications that demonstrate the use of modern frontend development, backend development, database management, authentication, and administrative functionality.

---

🛒 1. GadgetHub

Description

GadgetHub is an online gadget and accessories e-commerce platform that allows customers to browse available products, search and filter products, add products to a shopping cart, and place orders.

The system also provides administrative functionality for managing the products and platform.

Main Users

- Customers
- Administrators

Core Features

- User registration and login
- Product catalogue
- Product search
- Product filtering
- Shopping cart
- Checkout
- Order placement
- Admin dashboard
- Product management

---

🎓 2. CampusConnect

Description

CampusConnect is a student academic and course management system designed to allow students and school staff to manage courses, results, and other academic information digitally.

The platform provides separate functionality for students, lecturers, and administrators.

Main Users

- Students
- Lecturers
- Administrators

Core Features

- User authentication
- Course registration
- Result management
- Student dashboard
- Academic information management
- Announcements
- Admin dashboard

---

🏥 3. MediCare

Description

MediCare is a hospital appointment and patient management system designed to help hospitals manage patients, doctors, and appointments digitally.

The system provides different functionality for patients, doctors, and administrators.

Main Users

- Patients
- Doctors
- Administrators

Core Features

- Patient registration
- Patient management
- Doctor management
- Appointment booking
- Appointment management
- Admin dashboard
- Authentication

---

🛠️ Technology Stack

All three applications are planned to use the following technology stack:

Frontend

- React.js
- Tailwind CSS

React will be used to build the user interfaces and interactive components, while Tailwind CSS will be used for responsive and modern styling.

Backend

- Java
- Spring Boot

Spring Boot will provide the backend APIs and handle application logic, authentication, data processing, and communication between the frontend and database.

Database

- PostgreSQL

PostgreSQL will be used for storing and managing application data.

---

🏗️ General Architecture

The applications will follow a full-stack architecture:

┌─────────────────────────────┐
│          Frontend           │
│       React + Tailwind      │
└──────────────┬──────────────┘
               │
               │ HTTP / REST API
               ▼
┌─────────────────────────────┐
│           Backend           │
│       Java + Spring Boot    │
└──────────────┬──────────────┘
               │
               │ Database Queries
               ▼
┌─────────────────────────────┐
│          Database           │
│          PostgreSQL         │
└─────────────────────────────┘

---

🚀 How to Run the Projects

Prerequisites

Before running the applications locally, make sure the following are installed:

- Node.js
- npm
- Java JDK
- Maven
- PostgreSQL
- Git

---

1. Clone the Repository

git clone <YOUR-GITHUB-REPOSITORY-URL>

Navigate into the project directory:

cd <PROJECT-DIRECTORY>

---

2. Run the Frontend

Navigate to the appropriate frontend directory:

cd frontend

Install the required dependencies:

npm install

Start the development server:

npm run dev

The terminal will display the local development URL.

Open the provided URL in your browser.

---

3. Run the Backend

Open another terminal and navigate to the appropriate Spring Boot backend directory.

Using Maven:

mvn spring-boot:run

Alternatively, if the project includes the Maven wrapper:

Windows

mvnw.cmd spring-boot:run

macOS/Linux

./mvnw spring-boot:run

---

4. Configure PostgreSQL

Create a PostgreSQL database for the application.

The database connection details should be configured in the Spring Boot application's configuration file.

For example:

spring.datasource.url=jdbc:postgresql://localhost:5432/database_name
spring.datasource.username=your_username
spring.datasource.password=your_password

Replace the values with the appropriate PostgreSQL credentials.

Do not commit passwords, API keys, or other sensitive credentials to GitHub.

---

📂 Project Structure

The exact folder structure may evolve during development, but the project is expected to follow a structure similar to:

MMS3-Group-Project/
│
├── GadgetHub/
│   ├── frontend/
│   └── backend/
│
├── CampusConnect/
│   ├── frontend/
│   └── backend/
│
├── MediCare/
│   ├── frontend/
│   └── backend/
│
└── README.md

Each application will have its own frontend and backend components while following the same general technology stack.

---

🔐 Authentication & User Roles

The applications will support different user roles depending on the system.

GadgetHub

Customer
Admin

CampusConnect

Student
Lecturer
Admin

MediCare

Patient
Doctor
Admin

Role-based functionality will ensure that users can access the features relevant to their role.

---

🎯 Project Goals

The main goals of this project are to:

- Build functional full-stack applications
- Apply frontend development concepts using React
- Develop REST APIs using Java Spring Boot
- Work with relational databases using PostgreSQL
- Implement authentication and user roles
- Create responsive user interfaces
- Develop administrative dashboards
- Gain practical experience with collaborative software development
- Practice Git and GitHub-based teamwork

---

👥 Team Members

1. Olulana Oluwatosin Samuel

Role: Team Member / Developer

Contact: To be added

---

2. Fadiran Niniola Daniel

Role: Team Member / Developer

Contact: To be added

---

3. Adeyemo Kayode Kirtaneswara

Role: Team Member / Developer

Contact: To be added

---

4. Odumuyiwa Samuel Oluwadamilare

Role: Team Member / Developer

Contact: To be added

---

📞 Contact

Contact information for the team will be added as the project progresses.

---

📊 Project Status

🚧 In Development

The three applications are currently under development. Features, database structures, APIs, user interfaces, and administrative functionality will be implemented progressively.

---

📚 Academic Project

This project was developed as part of the MMS3 NIIT Software Engineering Project.

---

⭐ Applications

Project| Purpose| Main Users
🛒 GadgetHub| Online gadget & accessories e-commerce| Customers, Admins
🎓 CampusConnect| Student academic & course management| Students, Lecturers, Admins
🏥 MediCare| Hospital appointment & patient management| Patients, Doctors, Admins

---

Built collaboratively by the MMS3 Project Team.
