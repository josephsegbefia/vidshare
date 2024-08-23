# Vidshare

Vidshare is a video-sharing app built with React Native, Appwrite, and NativeWind. Users can sign in, share videos, and bookmark their favorite content.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Running the App](#running-the-app)
  - [Running on iOS](#running-on-ios)
  - [Running on Android](#running-on-android)
- [Expo Go](#expo-go)
- [Appwrite Setup](#appwrite-setup)
- [Troubleshooting](#troubleshooting)

## Features

- User authentication and sign-in
- Video upload and sharing
- Bookmark videos for easy access
- Smooth and responsive UI

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/en/download/) (LTS version recommended)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) (for iOS development)
- [Android Studio](https://developer.android.com/studio) (for Android development)

## Installation

Follow these steps to clone the repository and set up the app:

1. **Clone the Repository**

   ```bash
   git clone [https://github.com/yourusername/vidshare.git](https://github.com/josephsegbefia/vidshare.git)
   cd vidshare

   ```

2. **Install Dependencies**
   Make sure you have Expo CLI installed globally:
   ```bash
   npm install -g expo-cli

3. Then, install the project dependencies:

   ```bash
   npm install

   ```

4. **Running the App**
   You can run the app on either an iOS or Android device or emulator.

_Running on iOS_

- Open the iOS Simulator:

- Open Xcode.

- Go to Xcode > Preferences > Locations and set the Command Line Tools to the Xcode version you're using.

In the Terminal, run the following command to start the iOS Simulator:

```bash
expo start --ios
```

Run the App:

- The Expo CLI will open a new tab in your browser. Click on "Run on iOS Simulator."
- The app will automatically launch in the iOS Simulator.

Running on Android

- Open the Android Emulator:

  - Open Android Studio.
  - Launch the AVD Manager and start an emulator.
  - Alternatively, you can connect a physical Android device with USB debugging enabled.
    Run the App:

In the Terminal, run the following command to start the app on Android:

```bash
expo start --android
```

5. **Troubleshooting**

If you encounter any issues:

Ensure all dependencies are correctly installed.
Check that your device/emulator is properly set up and running.
Verify your Appwrite backend configuration.
