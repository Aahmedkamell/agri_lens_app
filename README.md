# 🌱 AgriLens

**AgriLens** is a Flutter-based agricultural application combining modern mobile UI with state management, local storage, remote networking, and Firebase integration.

## ✨ Features
- 🏠 Home dashboard with bottom navigation
- ⏱️ Timer workflow
- 📷 Scan workflow
- 🕘 History section
- ⚙️ Settings and profile-related screens
- 🌐 REST API communication using Dio
- 🔐 Firebase integration
- 💾 Local persistence
- 📊 Data visualization and searchable lists
- 🎨 Agricultural-focused UI

## 🛠️ Tech Stack
- **Flutter & Dart**
- **BLoC / Cubit**
- **Dio**
- **Firebase**
- **SQLite (sqflite)**
- **SharedPreferences**
- **FL Chart**
- **Google Fonts**
- **Flutter SVG**
- **Equatable**

## 🏗️ Architecture & Code Organization
```text
lib/
├── modules/
├── shared/
│   ├── cubit/
│   └── network/
├── firebase_options.dart
└── main.dart
```

The project uses Cubit for state management, Dio for remote communication, and shared layers for reusable application infrastructure.

## 🚀 Getting Started
```bash
git clone https://github.com/Aahmedkamell/argi_lens_app.git
cd argi_lens_app
flutter pub get
```

Configure the required Firebase project and platform configuration, then run:
```bash
flutter run
```

## 📸 Screenshots
Add screenshots under:
```text
assets/screenshots/
```

## 🎯 Technical Highlights
- State-driven UI with Cubit
- REST API integration
- Local persistence
- Firebase integration
- Search, filtering, charts, and date-selection components
- Modular and reusable Flutter code

## 👨‍💻 Author
**Ahmed Ashraf Mohammed Kamel**  
Flutter Developer
