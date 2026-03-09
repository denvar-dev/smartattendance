[smartattendance-README.md](https://github.com/user-attachments/files/25841580/smartattendance-README.md)
# 📋 Smart Attendance System

An Android-based attendance management system that replaces manual roll-call using face recognition, real-time cloud sync, and automated notifications. Built for and deployed at a real institution.

**Status:** Production — actively used by a client ✅

---

## 🎯 The Problem

Schools, colleges, and businesses waste time on manual attendance:
- Paper registers get lost or mishandled
- No real-time visibility for admins
- Parents/managers get no automatic updates
- No data for analysis or reporting

This system eliminates all of that.

---

## ✨ Features

- 📸 **Face Recognition** — Camera-based attendance marking, no manual input
- 🔐 **Firebase Authentication** — Secure login for teachers, admins, and students
- ☁️ **Firestore Real-time Database** — Attendance syncs instantly across all devices
- 📲 **Automated Notifications** — SMS and email alerts sent automatically on absence or late arrival
- 📊 **Admin Dashboard** — View attendance records, generate reports, manage users
- 🏫 **Multi-class Support** — Manage multiple classes and batches from one account

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Mobile App | Android (Java) |
| UI | XML Layouts |
| Authentication | Firebase Auth |
| Database | Firebase Firestore |
| Camera | Android Camera Intent |
| Notifications | SMS (Twilio) + Email (SMTP) |
| Face Detection | Android ML Kit |

---

## 📸 Screenshots

*(Add screenshots of the app here)*

---

## 🚀 Getting Started

### Prerequisites
- Android Studio (latest)
- Firebase account
- Android device or emulator (API 21+)

### Setup

```bash
git clone https://github.com/denvar-dev/smartattendance.git
cd smartattendance
```

1. Open the project in **Android Studio**
2. Connect your Firebase project:
   - Go to [Firebase Console](https://console.firebase.google.com)
   - Create a new project
   - Download `google-services.json` and place it in `/app`
3. Enable **Firebase Authentication** and **Firestore** in your Firebase console
4. Add your Twilio credentials in `config/NotificationConfig.java`
5. Run on device or emulator

---

## 🏗️ Project Structure

```
smartattendance/
├── app/
│   ├── src/main/java/
│   │   ├── auth/          # Firebase login & registration
│   │   ├── attendance/    # Face capture & marking logic
│   │   ├── dashboard/     # Admin & teacher views
│   │   ├── notifications/ # SMS & email dispatch
│   │   └── models/        # Data models (Student, Record, Class)
│   └── res/
│       └── layout/        # XML UI layouts
└── google-services.json   # Firebase config (not included — add your own)
```

---

## 📦 Real-World Deployment

This system was built for and deployed at a real educational institution in Pune, India. It replaced a fully manual attendance process and reduced admin workload significantly.

---

## 💼 Need This for Your Business?

I build custom versions of this system for:
- Schools and colleges
- Corporate offices
- Coaching centers and training institutes

Fully customized — your branding, your workflow, your data.

**Contact:** junaidpirjade1306@gmail.com
