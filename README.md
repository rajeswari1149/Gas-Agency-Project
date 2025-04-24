# Gas-Agency-Project
A gas-booking system using HTML, CSS, JS &amp; Firebase
# GoGas - Online Gas Booking System 🔥

A modern web-based gas booking system where users can register, book gas cylinders, track booking status, and manage their profiles. Admins can manage bookings and users efficiently using Firebase.

---

## 🚀 Features

### 👤 User Panel
- 🔐 User Registration with name, age, nationality, address, and profile picture
- 🔑 Secure Login (Firebase Authentication)
- 👤 View and update user profile in a modal
- 🛒 Book gas cylinders (max 12 per year)
- 📊 View real-time booking status
- 📜 View full booking history

### 🛠️ Admin Panel
- 🔐 Admin Login (role-based access)
- 📋 View all booking requests
- ✅ Accept or ❌ Reject bookings
- 🔄 Real-time updates using Firestore snapshots
- 🧑 Manage users and cylinder allocations

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS (Bootstrap), JavaScript
- **Backend/Realtime DB**: Firebase Firestore
- **Authentication**: Firebase Auth
- **File Storage**: Firebase Storage (profile pictures)
- **Hosting (Optional)**: Firebase Hosting

---

## 📁 Folder Structure

gas-booking-system/ ├── index.html # Landing Page ├── register.html # User Registration Page ├── login.html # User Login Page ├── homepage.html # User Dashboard ├── admin-login.html # Admin Login Page ├── admin-booking.html # Admin Dashboard for Booking Management ├── assets/ │ ├── css/ # Stylesheets │ ├── js/ # All JS files (homepage.js, admin-booking.js, etc.) │ └── images/ # Images & logos
