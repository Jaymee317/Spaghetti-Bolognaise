# Hackathon DriveScore 

An interactive mobile application developed for the hackathon, built using **React Native** and **Expo**. DriveScore aims to analyze driving habits, evaluate road safety metrics, and provide users with a personalized driving health score.

## Project Structure

This repository is organized as an Expo workspace. Below is an overview of the key directories:

```text
hackathon_drivescore/
├── .expo/                 # Expo build configuration and local cache files
├── DriveScore/            # Main React Native / Expo application source code
│   ├── assets/            # App icons, splash screens, and local images
│   ├── components/        # Reusable UI components
│   ├── screens/           # Core application views (e.g., Dashboard, Profile, Score Analysis)
│   ├── App.js / App.tsx   # Entry point for the React Native application
│   └── package.json       # Dependencies specific to the mobile application
└── README.md              # Project documentation
```

## Getting Started

Follow these steps to set up the project locally and test the application on your machine or mobile device.

### Prerequisites

Ensure you have the following installed on your system:
* [Node.js](https://nodejs.org) (v18 or higher recommended)
* npm or yarn
* [Expo Go](https://expo.dev) app installed on your physical iOS/Android device (optional, for rapid mobile testing)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Jaymee317/hackathon_drivescore.git
   cd hackathon_drivescore
   ```

2. **Navigate into the mobile project application folder:**
   ```bash
   cd DriveScore
   ```

3. **Install the dependencies:**
   ```bash
   npm install
   # OR if using yarn
   yarn install
   ```

### Running the Application

Start the Expo local development server:

```bash
npx expo start
```

Once the server initializes, an interactive QR code will appear in your terminal interface:
* **Physical Device:** Open your phone's camera (iOS) or the **Expo Go** app (Android) and scan the QR code to run the application live on your phone.
* **Emulators:** Press `a` in your terminal to open an Android Emulator, or `i` to open an iOS Simulator (requires Xcode on macOS).

## Tech Stack

* **Framework:** [Expo](https://expo.dev) & [React Native](https://reactnative.dev)
* **Language:** JavaScript / TypeScript
* **State Management & Tools:** React Hooks, Expo Router / React Navigation

## Contributors

* **Jaymee317** - [GitHub Profile](https://github.com/Jaymee317)
