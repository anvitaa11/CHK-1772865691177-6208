# HerSafe 🚨

**HerSafe** is a Flutter-based mobile application designed to enhance women's safety and health.
The app provides emergency assistance, live location tracking, trusted contact alerts, and health tracking features to help women stay safe and supported in critical situations.

---

# 📱 Features

### 🚨 SOS Emergency Button

Instantly alert trusted contacts during emergencies.

### 📍 Live Location Sharing

Share your real-time location with trusted contacts for safety monitoring.

### 🔊 Automatic Audio Recording

Automatically record audio during emergency situations for evidence.

### 👥 Trusted Contacts

Add and manage emergency contacts who will receive alerts and location updates.

### 📩 Emergency SMS Alerts

Send automated SMS messages with location details during emergencies.

### 🩺 Period Tracker

Track menstrual cycles and health-related information.

### 🎨 Simple and User-Friendly Interface

Designed with an intuitive and easy-to-use Flutter UI.

---

# 🛠️ Technologies Used

* **Flutter** – Cross-platform mobile app development
* **Dart** – Programming language used in Flutter
* **Firebase** – Backend services
* **Firebase Authentication** – User login and authentication
* **Cloud Firestore / Realtime Database** – Data storage
* **Firebase Storage** – Media storage
* **Google Maps / Location Services** – Live location tracking
* **Git & GitHub** – Version control and collaboration

---

# 📂 Project Structure

```
lib/
│
├── main.dart
├── homepage.dart
├── sos_page.dart
├── live_location.dart
├── trusted_contacts.dart
├── period_tracker.dart
├── automatic_recording.dart
├── automatic_msg.dart
├── emergencyrec.dart
├── onboardingpage.dart
├── theme/
│   └── app_theme.dart
```

---

# ⚙️ Installation Guide

Follow these steps to run the HerSafe app locally.

---

# 1️⃣ Install Prerequisites

Make sure the following tools are installed:

* Flutter SDK
* Dart SDK
* Android Studio or VS Code
* Git
* Firebase CLI

Check Flutter installation:

```
flutter doctor
```

---

# 2️⃣ Clone the Repository

```
git clone https://github.com/anvitaa11/hersafe.git
cd hersafe
```

---

# 3️⃣ Install Dependencies

```
flutter pub get
```

---

# 4️⃣ Setup Firebase Backend

### Create Firebase Project

1. Go to **Firebase Console**
2. Click **Add Project**
3. Enter project name
4. Create the project

---

### Register Android App

1. Click **Add App**
2. Select **Android**
3. Enter package name from:

```
android/app/src/main/AndroidManifest.xml
```

---

### Download Firebase Configuration

Download:

```
google-services.json
```

Place it inside:

```
android/app/google-services.json
```

---

# 5️⃣ Configure Firebase in Flutter

Install Firebase CLI:

```
npm install -g firebase-tools
```

Login to Firebase:

```
firebase login
```

Install FlutterFire CLI:

```
dart pub global activate flutterfire_cli
```

Configure Firebase:

```
flutterfire configure
```

This generates the file:

```
lib/firebase_options.dart
```

---

# 6️⃣ Run the Application

Start an emulator or connect a device.

Run the app:

```
flutter run
```

For web:

```
flutter run -d chrome
```

---

# 📦 Build APK

To generate a release APK:

```
flutter build apk
```

APK location:

```
build/app/outputs/flutter-apk/app-release.apk
```

---

# 🔧 Troubleshooting

If dependencies fail:

```
flutter clean
flutter pub get
```

Check connected devices:

```
flutter devices
```

---

# 🚀 Future Improvements

* AI-based danger detection
* Voice-activated SOS system
* Integration with police emergency services
* Wearable device support
* Offline emergency alerts

---

# 👨‍💻 Author

Developed by **ANVITA AWCHARE AND NAJIYA PATEL**

---

# ⭐ Support

If you like this project, please give it a **star ⭐ on GitHub**.
