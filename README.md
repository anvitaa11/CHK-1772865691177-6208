HerSafe 🚨

HerSafe is a safety-focused application designed to help women stay secure by providing quick access to emergency assistance, real-time location sharing, and instant alerts to trusted contacts. The goal of HerSafe is to create a reliable digital safety companion that can be used during emergencies.

🌟 Features

Emergency SOS Button – Instantly send alerts to emergency contacts.

Live Location Sharing – Share real-time location with trusted people.

Quick Dial Emergency Contacts – Call predefined contacts with one tap.

Safety Alerts – Send notifications during dangerous situations.

User-Friendly Interface – Simple and easy-to-use design for quick actions during emergencies.

---

# 🛠️ Technologies Used

* **Flutter** – Mobile App Development
* **Dart** – Programming Language
* **Firebase** – Backend Services
* **Firebase Authentication** – User Authentication
* **Cloud Firestore / Realtime Database** – Data Storage
* **Firebase Storage** – Media Storage
* **Google Maps / Location Services** – Live Location Tracking
* **Git & GitHub** – Version Control

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
├── theme/
│   └── app_theme.dart
```

---

# ⚙️ Installation Guide

Follow the steps below to run the project locally.

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

Fix any issues shown in the result.

---

# 2️⃣ Clone the Repository

```
git clone https://github.com/your-username/women_safety_health_app.git
cd women_safety_health_app
```

---

# 3️⃣ Install Project Dependencies

```
flutter pub get
```

---

# 4️⃣ Setup Firebase Backend

### Step 1: Create Firebase Project

1. Go to Firebase Console
2. Click **Add Project**
3. Enter project name
4. Create the project

---

### Step 2: Register Android App

1. Click **Add App**
2. Select **Android**
3. Enter package name from:

```
android/app/src/main/AndroidManifest.xml
```

---

### Step 3: Download Configuration File

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

This generates:

```
lib/firebase_options.dart
```

---

# 6️⃣ Run the Application

Start an emulator or connect a device.

Then run:

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

Check available devices:

```
flutter devices
```

---

# 🚀 Future Improvements

* AI-based danger detection
* Voice-activated SOS system
* Integration with police emergency services
* Smart wearable device integration
* Offline emergency alerts

---

# 👨‍💻 Author

Developed by **Your Name**

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you like this project, please give it a **star ⭐ on GitHub** to support development.
