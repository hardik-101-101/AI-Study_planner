# AI-Study_planner

GitHub ke liye **Short Description (About section)** aur complete **README Description** dono ready hain:

---

### 📌 1. Short Repo Description *(GitHub ke 'About' box ke liye - Copy & Paste)*

> **A cross-platform AI-powered Study Planner and productivity app built with Flutter & Firebase. Features smart timetable generation, Pomodoro focus timer, exam & task trackers, offline persistence, and analytics.**

*(Tags / Topics to add on GitHub: `flutter`, `dart`, `study-planner`, `productivity`, `pomodoro`, `firebase`, `offline-first`, `cross-platform`)*

---

### 📄 2. Complete README Description *(README.md ke liye)*

```markdown
# 📚 AI Study Planner & Focus Tracker

[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart&logoColor=white)](https://dart.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Auth%20%7C%20Firestore-FFCA28?logo=firebase&logoColor=black)](https://firebase.google.com)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Web%20%7C%20Linux-brightgreen)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](#)

An intelligent, cross-platform productivity and study scheduling app designed to help students optimize their daily revision, stay on top of upcoming exams, and maintain consistent focus routines.

---

## 🌟 Key Features

- **🧠 Smart AI Timetable Generation:** Automatically allocates realistic study sessions based on subject priority, difficulty levels, and user-defined preferred study hours.
- **⏱️ Dual Focus Timer & Stopwatch:** Integrated Pomodoro countdown timer and count-up stopwatch that automatically logs focus minutes to daily productivity metrics.
- **📖 Subject, Task & Exam Management:** Manage subject syllabus, track subtasks with dynamic progress meters, and view upcoming exam countdowns.
- **📈 Real-Time Analytics & Streak Tracking:** Visualizes weekly focus duration, completion percentages, subject breakdown, and active study streaks.
- **📶 Offline-First Architecture:** 100% functional without internet connectivity using `SharedPreferences` with robust JSON serialization.
- **🔔 Local Notifications & Reminders:** Scheduled local notifications for daily study sessions and exam alerts using `flutter_local_notifications`.
- **🎨 Dynamic Theme Support:** Seamlessly switch between Light, Dark, and System-adaptive themes.

---

## 🛠️ Tech Stack & Architecture

- **Framework:** [Flutter](https://flutter.dev/) (Mobile, Web & Desktop)
- **Language:** [Dart](https://dart.dev/)
- **Backend & Authentication:** Firebase (Firebase Auth, Cloud Firestore)
- **Local Storage:** `SharedPreferences` (JSON data modeling)
- **State Management:** `ChangeNotifier` & `ListenableBuilder` (Reactive UI)
- **Architecture Pattern:** Service / Repository Pattern with Singleton Services

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (>= 3.x)
- Android Studio / VS Code / Chrome Browser

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ai-study-planner.git
   cd ai-study-planner
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run on your device:**
   - **Android:**
     ```bash
     flutter run
     ```
   - **Web Browser:**
     ```bash
     flutter run -d web-server --web-port=8080
     ```
```
