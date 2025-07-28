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

### Doctor Login (access via admin panel link)
- Email: emilylarson@gmail.com  
- Password: emilylarson@123

### User/Patient Login
- Email: user1@gmail.com  
- Password: 12345678

> Admin and Doctor share a common panel at: https://prescripto-fullstack-admin.onrender.com  
> Patients access the user frontend at: https://prescripto-fullstack-frontend-47b3.onrender.com

---

## Features

- Patient, Doctor, and Admin login/signup
- JWT-based authentication and role-based routing
- Admin can manage doctors and view appointments
- Doctors can manage their availability and appointments
- Patients can view doctors and book appointments
- Razorpay integration for appointment payments
- Admin dashboard showing key metrics and recent activity

---

## Tech Stack

- Frontend: React.js
- Backend: Node.js with Express
- Database: MongoDB
- Authentication: JWT (JSON Web Tokens)
- Deployment: Render

---

## Notes

- Admin must approve doctors before they can receive appointments
- Doctors and admins use the same panel but have role-based views
- Patients use a separate frontend for booking and managing appointments

