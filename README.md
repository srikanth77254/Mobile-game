# 🎮 Mobile Games with AI

> Build, test, and publish Android games using **React Native (Expo)**, **AI-assisted development**, and **Google Play Console**.

![Platform](https://img.shields.io/badge/Platform-Android-green)
![Framework](https://img.shields.io/badge/Framework-React%20Native-blue)
![Expo](https://img.shields.io/badge/Expo-SDK-black)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

This repository demonstrates the complete workflow for developing Android games with the assistance of AI coding tools. It serves as a learning resource for beginners and intermediate developers who want to understand the end-to-end mobile application development process—from project creation to publishing on the Google Play Store.

The reference project used throughout this repository is **Space Escape Runner**, but the workflow can be applied to virtually any Android game or application.

Rather than focusing on one specific game, this project emphasizes **incremental development**, **prompt engineering**, **testing**, and **deployment** using modern development tools.

---

## ✨ Features

* AI-assisted mobile app development
* Beginner-friendly React Native project
* Expo development workflow
* Responsive game UI
* Spaceship movement controls
* Random asteroid generation
* Collision detection
* Score tracking
* High score persistence using AsyncStorage
* Restart game functionality
* Modern UI enhancements
* Android APK generation
* Android AAB generation
* Google Play Store publishing guide

---

## 🎯 Learning Outcomes

By completing this project, you will learn how to:

* Build Android apps using React Native
* Work with Expo and Expo Go
* Develop games incrementally using AI prompts
* Manage application state
* Implement game mechanics
* Persist local data
* Generate production Android builds
* Publish apps on Google Play

---

# 🛠 Tech Stack

| Technology                      | Purpose                           |
| ------------------------------- | --------------------------------- |
| React Native                    | Cross-platform mobile development |
| Expo                            | Development framework             |
| Expo Go                         | Live testing on Android           |
| Expo Application Services (EAS) | Cloud builds                      |
| AsyncStorage                    | Local storage                     |
| Cursor / VS Code + AI           | AI-assisted development           |
| Git & GitHub                    | Version control                   |

---

# 📂 Project Structure

```text
mobile-games/
│
├── app/
│   ├── src/
│   ├── build.gradle.kts
│   └── ...
│
├── .env.example
├── .gitignore
├── README.md
└── ...
```

---

# 🚀 Getting Started

## Prerequisites

Before running the project, install:

* Node.js (LTS)
* npm or Yarn
* Expo CLI
* Expo Go (Android)
* Git
* Cursor or Visual Studio Code

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/mobile-games.git
```

Navigate into the project:

```bash
cd mobile-games
```

Install dependencies:

```bash
npm install
```

Start the Expo development server:

```bash
npx expo start
```

Scan the generated QR code using the **Expo Go** app on your Android device to launch the application.

---

# 📖 Development Workflow

The project is built incrementally using AI-assisted prompts.

## Phase 1 – Project Setup

* Create Expo project
* Configure development environment
* Build initial game screen

## Phase 2 – Player Movement

* Spaceship creation
* Left/Right controls
* Boundary detection

## Phase 3 – Gameplay

* Falling asteroids
* Random spawning
* Collision detection
* Score system

## Phase 4 – Persistence

* Restart functionality
* High score storage using AsyncStorage

## Phase 5 – UI Improvements

* Gradient background
* Smooth animations
* Modern styling

## Phase 6 – Android Build

Generate production builds using:

* Expo Application Services (EAS)
* Android APK
* Android App Bundle (AAB)

## Phase 7 – Publishing

Complete workflow for:

* Google Play Developer Account
* Store Listing
* App Signing
* Internal Testing
* Closed Testing
* Production Release

---

# 📱 Testing

The application should be tested after every feature implementation using **Expo Go** to ensure functionality before moving to the next development phase.

---

# 📦 Build

Generate Android builds with Expo Application Services:

```bash
eas build --platform android
```

Available build outputs:

* APK (Testing)
* AAB (Google Play Submission)

---

# 🚀 Deployment

Once the Android App Bundle (.aab) is generated, it can be uploaded to the Google Play Console for review and publication.

The publishing process includes:

* Store listing
* Screenshots
* Privacy Policy
* Data Safety declaration
* Content Rating
* App Signing
* Production release

---

# 📚 Repository Goals

This project is designed to help developers:

* Learn React Native fundamentals
* Understand AI-assisted software development
* Build Android games step-by-step
* Practice prompt engineering
* Create production-ready mobile applications

---

# 🤝 Contributing

Contributions are welcome.

If you find bugs, have suggestions, or would like to improve the project, feel free to:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for educational and personal purposes.

---

# 🙏 Acknowledgements

Special thanks to the React Native, Expo, and open-source communities for providing the tools and resources that make modern mobile development accessible.

This repository was created as part of an AI-assisted Android game development learning journey and demonstrates the complete workflow from idea to deployment.

---

