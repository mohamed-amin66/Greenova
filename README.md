# 🌱 Greenova

**An Offline-First Agricultural Management Application**

Greenova is a mobile application designed to help farmers manage their agricultural activities efficiently. Built with Flutter and Dart, it works offline using a local SQLite database, allowing users to access their farm data without an internet connection.

## 🎯 Project Objectives

* Simplify agricultural management through a single mobile application.
* Monitor plant health and keep track of crop development.
* Manage agricultural plots and their geographical information.
* Track harvests, expenses, sales, and profitability.
* Organize agricultural inventory and stock movements.
* Plan irrigation activities and receive local reminders.
* Protect user data through local authentication.

## ✨ Main Features

### 🌿 Plant Health & Growth

* Register and manage plants and crops.
* Capture plant photos using the device camera.
* Record symptoms, treatments, and health history.
* Explore local AI-based disease recognition.

### 🗺️ Agricultural Plots

* Create, update, and delete agricultural plots.
* Record GPS coordinates and estimate plot areas.
* Use smartphone motion sensors for basic terrain information.

### 👨‍🌾 Farmer Profile & Security

* Manage the farmer's local profile.
* Support biometric authentication when available.
* Provide PIN authentication as a fallback.
* Automatically lock the application when appropriate.

### 🌾 Harvests & Profitability

* Record harvest quantities and sales.
* Track agricultural expenses.
* Estimate yields and profits.
* Compare results across seasons.

### 📦 Inventory Management

* Manage seeds, fertilizers, and agricultural treatments.
* Track stock movements and expiration dates.
* Receive low-stock and expiration alerts.

### 💧 Irrigation & Planning

* Schedule irrigation activities.
* Receive local notifications and reminders.
* Record irrigation duration and estimated water usage.

## 🛠️ Technologies

* **Flutter** — Cross-platform mobile development
* **Dart** — Application programming language
* **SQLite** — Offline local database
* **Drift** — Type-safe database management
* **GPS / Geolocation** — Plot location information
* **Camera** — Plant photos and optional receipt capture
* **Sensors Plus** — Smartphone motion sensors
* **Local Authentication** — Biometrics and device authentication
* **Flutter Local Notifications** — Reminders
* **TensorFlow Lite** — Potential on-device AI integration

## 📴 Offline-First Design

Greenova stores its data locally, allowing its core features to work without an internet connection. Internet access is not required for normal farm management operations.

## 👥 Team

Greenova is developed collaboratively by a team of six members. Each member is responsible for a project module and contributes to implementation, testing, and documentation.

## 🚀 Getting Started

### Prerequisites

* Flutter SDK
* Dart SDK
* Android Studio or Visual Studio Code
* Android emulator or a compatible Android device

### Installation

1. Clone the repository:

   ```bash
   git clone <YOUR_REPOSITORY_URL>
   ```

2. Open the project directory:

   ```bash
   cd Greenova
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the application:

   ```bash
   flutter run
   ```

> **Note:** Some features, including AI-based recognition and biometric authentication, may require additional configuration and implementation.

## 📌 Project Status

🚧 Under development.

---

*Greenova — Smarter tools for more organized farming.*
