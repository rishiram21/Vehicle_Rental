# 🚗 Vehicle Rental System
🌐 Built with React, Spring Boot & MySQL
A full-stack web application for managing vehicle rentals, from customer booking to admin control, designed to streamline the rental process with a modern tech stack.

🛠️ Tech Stack
Frontend: React.js (Hooks, Axios, React Router)

Backend: Spring Boot (REST APIs, Spring Security, JPA/Hibernate)

Database: MySQL (relational storage)

Others: JWT (auth), Bootstrap or Tailwind (UI), Postman (API testing)

🎯 Project Objective
To build a scalable and user-friendly platform that allows users to browse, book, and manage vehicle rentals, while enabling admins to add vehicles, track bookings, and handle reports via a secure dashboard.

👤 User Roles
🔒 Admin
Manage all vehicles (CRUD)

Approve/deny bookings

Monitor vehicle availability

View rental reports and user data

👤 Customer
Register/login (JWT-secured)

View and filter available vehicles

Book a vehicle for selected dates

View booking history and rental status

Cancel or modify existing bookings

📁 Key Modules
✅ 1. Authentication (JWT + Spring Security)
Signup / login / logout

Role-based access control

🚘 2. Vehicle Management
Admin: Add/edit/delete vehicle data

Vehicles include details: model, brand, price/day, fuel type, image, status

📝 3. Booking System
Select vehicle + date range (calendar picker)

Auto-check for availability

Rent cost calculation

Booking confirmation and summary

📦 4. Customer Dashboard
View current and past bookings

Cancel or reschedule options

Display invoice (optional)

📊 5. Admin Dashboard
Overview of active rentals, vehicle availability

User management

Optional: charts showing usage, earnings

🗃️ 6. Database Design (MySQL)
users – stores customer/admin login info

vehicles – vehicle catalog

bookings – rental details (user ID, vehicle ID, dates)

payments – optional payment module

📊 APIs Structure (Spring Boot)
POST /api/auth/register

POST /api/auth/login

GET /api/vehicles

POST /api/bookings

GET /api/bookings/user/{id}

PUT /api/vehicles/{id} (admin only)

🌟 Features
Responsive UI using React

RESTful APIs with error handling

JWT-secured login

Real-time vehicle availability

Modular structure for scalability


