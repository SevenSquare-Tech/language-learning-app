# LangApp

LangApp is a Flutter-based mobile application focused on language-related features such as translation, speech-to-text, text-to-speech, authentication, and cloud-based storage using Firebase.

---

## 📱 Features

- User authentication (Email & Google Sign-In)
- Multi-language support
- Text translation
- Speech to Text & Text to Speech
- Firebase Firestore & Storage integration
- Local data storage using Hive
- Animated UI components
- Image picking and processing
- Signature pad support
- Permission handling
- Offline support with Shared Preferences

---

## 🛠 Tech Stack

- **Framework:** Flutter
- **State Management:** Provider, GetX
- **Backend Services:** Firebase (Auth, Firestore, Storage)
- **Local Storage:** Hive, Shared Preferences
- **APIs & Services:** Google Vision API, Google Auth
- **UI & Animations:** Lottie, Animate Do, Animated Text Kit

---

## 📦 Dependencies

Key packages used in this project:

- firebase_core
- firebase_auth
- cloud_firestore
- firebase_storage
- google_sign_in
- translator
- speech_to_text
- flutter_tts
- hive & hive_flutter
- provider & get
- image_picker
- permission_handler
- http
- intl
- flutter_svg

(Refer to `pubspec.yaml` for the complete list)

---

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (>= 2.19.4 < 3.0.0)
- Dart SDK
- Android Studio / VS Code
- Firebase Project setup

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/SevenSquare-Tech/language-learning-app
   ```

2. Navigate to the project directory:

   ```bash
   cd language-learning-app
   ```

3. Install dependencies:

   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

---

## 🔐 Firebase Setup

- Create a Firebase project
- Enable Authentication (Email & Google)
- Setup Firestore & Storage
- Download `google-services.json` (Android) / `GoogleService-Info.plist` (iOS)
- Place them in respective platform folders

---

## 📂 Assets

Assets used in this project:

- Images: `assets/`
- Flags: `assets/flag/`
- Fonts: Ubuntu (Rubik-Regular.ttf)

---

## 🧪 Testing

Run Flutter tests using:

```bash
flutter test
```

---

## 🧩 Build

### Android

```bash
flutter build apk
```

### iOS

```bash
flutter build ios
```
