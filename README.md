# 🚚 Fasttrack – Logistics & Delivery Management System

Fasttrack is a logistics and delivery management system designed to streamline package assignment, delivery tracking, and route optimization across warehouses. It consists of a **Flask-based web portal** and a **Flutter mobile application** used by delivery personnel.

---

## 🎯 Project Objective

To build a unified system for logistics companies that:
- 📦 Uploads and manages delivery packages
- 🚴 Assigns deliveries to available delivery personnel
- 📍 Optimizes delivery routes using a **Greedy Algorithm**
- 📱 Enables delivery boys to view, track, and complete deliveries via a mobile app

---

## 🧠 Key Features

### 🖥️ Website
- 🏢 Company login and dashboard
- 📦 Upload package details (location, weight, destination, etc.)
- 🤖 Automatically assigns packages using distance/availability-based logic
- 🧠 Uses a **Greedy Algorithm** for route optimization per delivery boy
- 📊 View reports, employee data, complaints

### 📱 Mobile App (Delivery Personnel)
- 🔐 Login and authentication
- 📋 View assigned packages
- 📌 Real-time display of **optimized delivery route**
- ✅ Mark packages as picked up or delivered
- 📍 GPS and location integration

---

## 🔐 Technologies Used

- **Frontend (Web)**: HTML, CSS, JavaScript (Flask Templates)
- **Backend**: Python Flask
- **Mobile App**: Flutter (Dart)
- **Database**: Firebase Firestore
- **Authentication**: Firebase + Supabase
- **Email Notifications**: Gmail SMTP
- **Routing Algorithm**: Greedy approach for route optimization

---

## 📄 License

This project is part of an academic submission and not intended for commercial deployment without further improvements and security audits.

---

## 🌐 Useful Links

- [Flutter Docs](https://flutter.dev/docs)
- [Supabase](https://supabase.com/)
- [Firebase Console](https://console.firebase.google.com/)
- [Flask Docs](https://flask.palletsprojects.com/)
