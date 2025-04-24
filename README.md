# Gas-Agency-Project
A gas-booking system using HTML, CSS, JS &amp; Firebase

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

## 🔧 Update Your Firebase Config

Before running the application, update your Firebase configuration in all JavaScript files that initialize Firebase (like `homepage.js`, `admin-booking.js`, etc.).

### ✅ Steps:
1. Go to your [Firebase Console](https://console.firebase.google.com/).
2. Click on your project > ⚙️ Project Settings > scroll to **Your Apps**.
3. Copy the Firebase SDK snippet (the `firebaseConfig` object).
4. Replace the existing `firebaseConfig` in your JavaScript files:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT.appspot.com",
  messagingSenderId: "YOUR_MESSAGING_ID",
  appId: "YOUR_APP_ID"
};
```

---

## 📁 Folder Structure

gas-booking-system/ ├── index.html # Landing Page ├── register.html # User Registration Page ├── login.html # User Login Page ├── homepage.html # User Dashboard ├── admin-login.html # Admin Login Page ├── admin-booking.html # Admin Dashboard for Booking Management ├── assets/ │ ├── css/ # Stylesheets │ ├── js/ # All JS files (homepage.js, admin-booking.js, etc.) │ └── images/ # Images & logos
