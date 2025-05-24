# 🌾 Farmers Connect

**Empowering farmers with technology for a sustainable future.**

Farmers Connect is a full-stack mobile application designed to revolutionize the way farmers interact with the digital ecosystem. It provides essential tools for market access, crop diagnostics, weather forecasts, expert advice, and real-time agricultural insights.

---

## 📱 Features

### 🔐 Secure Authentication
- Google OAuth integration
- Firebase-based user authentication
- Engaging animated login interface

### 📰 News Dashboard
- Dynamic daily updates on agricultural and weather news
- Displayed as notification cards on the home screen

### 🌱 Plant Disease Detection
- Integrated TensorFlow Lite (TFLite) ML model
- Detects 27 plant diseases from user-submitted images
- Built using `flutter_tflite` package

### 🛒 Marketplace with Geolocation
- Farmers can list and sell produce
- Products fetched based on user’s location radius
- Real-time data storage in Firebase Realtime Database

### 🌦️ Weather Forecast
- Live weather updates: temperature, moisture, wind speed
- Enables better planning for crop maintenance

### 👤 Profile Management
- Customizable user information
- App settings and preferences

### 🧠 Expert Tools (Miscellaneous)
- Access to additional tools and APIs
- Potential to expand into expert advisory and more

---

## 💻 Technologies Used

- **Frontend:** Flutter
- **Backend:** Firebase (Authentication + Realtime DB)
- **Machine Learning:** TensorFlow Lite (TFLite)
- **Geolocation:** Integrated location services
- **APIs:** Weather & News APIs for real-time data
- **CI/CD:** GitHub Actions (for automated build/deployment)

---

## 📸 Screenshots

> _Add screenshots or GIFs here showing app UI, disease detection in action, and the marketplace interface._

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK
- Firebase project setup
- TFLite trained model file (included or linked)
- Android/iOS emulator or physical device

### Installation

```bash
git clone https://github.com/yourusername/farmers-connect.git
cd farmers-connect
flutter pub get
flutter run
