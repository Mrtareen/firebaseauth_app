# FirebaseAuthApp 🚀

## Overview
This Flutter app integrates Firebase authentication, allowing users to **sign up, log in, and log out** using **email and password**.

## Features
- **Firebase Authentication (Email/Password)**
- **User Sign-Up & Login**
- **Profile Screen Display**
- **Error Handling**

## Installation
1. **Install Flutter** from [flutter.dev](https://flutter.dev).
2. **Clone the repository**:
   git clone https://github.com/your-repo/firebase-auth-app.git cd firebase-auth-app

## Firebase Setup
1. **Go to** [Firebase Console](https://console.firebase.google.com/)
2. **Create a Firebase project**
3. **Enable Authentication** → Navigate to **Authentication** > **Sign-in method** > Enable **Email/Password**
4. **Download `google-services.json`** and place it in:
5. android/app/google-services.json
6. **Initialize Firebase in `main.dart`**:
```dart
await Firebase.initializeApp();

## Project Structure
firebase_auth_app/
│── lib/
│   ├── main.dart
│   ├── auth_service.dart
│   ├── login_screen.dart
│   ├── profile_screen.dart
│── android/app/src/main/AndroidManifest.xml
│── pubspec.yaml
│── README.md
