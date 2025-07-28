# Prescripto - Full Stack Medical Appointment & Prescription System

Prescripto is a full-stack web application for booking doctor appointments and managing prescriptions. It includes separate interfaces for admin, doctors, and patients.

---

## Live Links

- Frontend (Patients): https://prescripto-fullstack-frontend-47b3.onrender.com  
- Admin & Doctor Panel: https://prescripto-fullstack-admin.onrender.com  
- Backend API: https://prescripto-fullstack-backend.onrender.com

---

## Demo Credentials

### Admin Login
- Email: navneet.889035@gmail.com  
- Password: navneet@039

### Doctor Login (Access via same link as Admin)
- Email: emilylarson@gmail.com  
- Password: emilylarson@123

> Both Admin and Doctor login use the same panel link: https://prescripto-fullstack-admin.onrender.com

---

## Features

- Patient and Doctor login/signup
- Admin and Doctor share a unified panel (role-based access)
- JWT-based authentication
- Admin can manage doctors and appointments
- Doctors can view appointments and manage availability
- Patients can search and book doctor appointments
- Razorpay payment integration
- Admin dashboard with basic analytics

---

## Tech Stack

- Frontend: React.js
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT
- Deployment: Render

---

## Notes

- Admin and Doctor dashboards are role-based under a shared route
- Patients access a separate frontend
- All roles are authenticated using JWT

