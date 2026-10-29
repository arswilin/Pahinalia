# Pahinalia

## About the App
Pahinalia is a mobile application developed using Flutter. This repository contains the source code for the application.

## Requirements
Before installing or running the app, make sure you have the following:

- Flutter SDK
- Android Studio or Visual Studio Code
- Android phone or emulator
- USB cable for testing on a physical device (optional)

## Installation Guide

### 1. Clone the Repository
Open a terminal or PowerShell and run:

```bash
git clone https://github.com/arswilin/Pahinalia.git
```

### 2. Open the Project Folder

```bash
cd Pahinalia
```

### 3. Install Dependencies

```bash
flutter pub get
```

### 4. Run the Application

Connect your Android phone or start an emulator, then run:

```bash
flutter run
```

### 5. Build the APK

To create an Android APK file for installation, run:

```bash
flutter build apk --release
```

After the build completes, the APK will be located at:

```text
build/app/outputs/flutter-apk/app-release.apk
```

### 6. Install the APK on Your Android Phone

1. Copy `app-release.apk` to your Android phone.
2. Open the APK file.
3. Allow installation from this source if Android asks for permission.
4. Tap **Install**.
5. Open Pahinalia after installation.

## Troubleshooting

- If dependencies are missing, run `flutter pub get`.
- If the build fails, run `flutter doctor` to check your Flutter setup.
- Make sure your Android SDK and required build tools are installed.

## Repository

GitHub: https://github.com/arswilin/Pahinalia

## Developer

Developed as a Flutter application project.
