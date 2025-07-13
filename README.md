## Expo Go Setup Documentation

### Objective

Mobile development with React Native requires device testing, which traditionally involves emulators that demand significant hardware resources. To streamline the development process and avoid these hardware constraints, we’re using the Expo Framework. It allows direct app testing on physical devices using the Expo Go app, making development faster, smoother, and more accessible.

### Prerequisites

Before starting this task, the following tools were already installed:

- Node.js LTS – for JavaScript runtime and project setup  
- Visual Studio Code – recommended IDE for editing and managing the codebase  
- Compatible OS – using macOS / Linux / Windows (user-specific)  
- Physical iOS device – for testing the mobile application  

### Expo Go Installation Process (iOS)

1. Visited the [official Expo Go homepage](https://expo.dev/go).
2. Selected the latest SDK version (done automatically based on the Expo Go version).
3. Installed the Expo Go app via the Apple App Store.
4. Opened the app on my iPhone.
5. Created an Expo account and successfully logged in.

### Purpose of Using Expo Go

- Eliminates the need for heavy Android or iOS emulators.
- Allows real-time preview and testing of React Native apps on a real device.
- Supports QR code scanning for instant app deployment during development.
- Cross-platform: works equally well for Android and iOS devices.

### Challenges Faced

No issues encountered during installation and setup.  
The process was smooth and the app was ready for use immediately after login.
~

------------

# Expo Router Project Setup

## Objective

Set up a React Native mobile application using the Expo Router template and understand the project structure. Document the setup process and behavior after resetting the project.

## Steps Followed

### 1. Navigate to Project Directory

```bash
cd prodev-mobile-setup
2. Initialize Expo Project
bash
Copy
Edit
npx create-expo-app@latest .
3. Modify Home Screen
Edited the file:

bash
Copy
Edit
app/(tabs)/index.tsx
Changed:

tsx
Copy
Edit
Welcome!
To:

tsx
Copy
Edit
** First App Created **
4. Start the Project
bash
Copy
Edit
npx expo start
Scanned the QR code using the Camera app on iOS to preview the app with Expo Go.

5. Reset the Project
bash
Copy
Edit
npm run reset-project
What Happened After Running reset-project
Cleared Metro bundler cache and development build state.

Removed temporary files.

Helped resolve issues related to stale or inconsistent builds.

Ensured the app restarted cleanly on the next run.