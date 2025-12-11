![Flutter](https://img.shields.io/badge/Flutter-Mobile%20App-blue)
![Firebase](https://img.shields.io/badge/Firebase-Backend-yellow)
![Firestore](https://img.shields.io/badge/Cloud%20Firestore-Realtime%20DB-orange)
![Figma](https://img.shields.io/badge/Figma-Design-red)
![Platform](https://img.shields.io/badge/Platforms-Android%20%7C%20iOS-lightgrey)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

# 🎓 EWI – University System Mobile Application

EWI is a modern, cross-platform **University System Mobile Application** designed to simplify and digitalize academic and administrative experiences for **students**, **faculty**, and **university staff**.

It provides seamless access to course management, schedules, academic records, notifications, and secure university resources — all in one place.

---

## 🚀 Features

* 🔐 **User Authentication**
  Role-based access: *student, faculty, administrator*

* 📅 **Academic Calendar & Events**
  Integrated calendar with event reminders and deadlines.

* 📝 **Course Registration & Enrollment**
  Add, drop, and manage courses easily.

* ⏰ **Schedule Management**
  View lectures, labs, and personalized weekly timetables.

* 📊 **Academic Records**
  Access grades, attendance, and transcript history.

* 🔔 **Real-time Notifications**
  Instant updates for announcements, deadlines, and alerts.

* 📄 **Secure File Handling**
  Upload and download university-related documents.

---

## 🏗️ Tech Stack

| Layer              | Technology Used  |
| ------------------ | ---------------- |
| **Frontend**       | Flutter          |
| **Backend**        | Firebase         |
| **Database**       | Cloud Firestore  |
| **Authentication** | Firebase Auth    |
| **Cloud Storage**  | Firebase Storage |
| **Design (UI/UX)** | Figma            |

---

## 🧱 Architecture

```
         ┌──────────────────────────────┐
         │        Flutter App           │
         │ (Students / Faculty / Admin) │
         └──────────────┬──────────────┘
                        │
                Realtime API Calls
                        │
         ┌─────────────────────────────────┐
         │          Firebase Backend        │
         │  ┌────────────────────────────┐  │
         │  │  Cloud Firestore (DB)      │  │
         │  │  Firebase Auth (Users)     │  │
         │  │  Firebase Storage (Files)  │  │
         │  └────────────────────────────┘  │
         └─────────────────────────────────┘
```

---

## 📁 Project Structure

```
EWI/
├── lib/                     # Main application logic, screens, widgets
│   ├── screens/             # UI screens
│   ├── widgets/             # Shared components
│   ├── models/              # Data models
│   ├── services/            # Firestore/Auth helpers
│   ├── utils/               # Constants & helpers
│   └── main.dart            # App entry point
│
├── auth_repository/         # Dedicated authentication logic
│
├── assets/                  # Images, icons, and fonts
│
├── android/                 # Android configuration
│
├── ios/                     # iOS configuration
│
└── project_structure.txt    # Full detailed project structure
```

---

## 🔧 Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/AbdullahAlassi/university-system-app.git
cd university-system-app
```

### 2️⃣ Install Dependencies

```
flutter pub get
```

### 3️⃣ Configure Firebase

#### For Android:

Add your downloaded `google-services.json` here:

```
android/app/google-services.json
```

#### For iOS:

Add your `GoogleService-Info.plist` here:

```
ios/Runner/GoogleService-Info.plist
```

### 4️⃣ Run the Application

```
flutter run
```

---

## 🤝 Contributing

Contributions are welcome!

```
# Create your feature branch
git checkout -b feature-name

# Commit your changes
git commit -m "Add new feature"

# Push your branch
git push origin feature-name
```

Open a Pull Request and your changes will be reviewed.

---

## 📜 License

This project is licensed under the **MIT License**.

## 📞 Contact
Email: abdullah.alassi123@gmail.com
Github: https://github.com/AbdullahAlassi/
