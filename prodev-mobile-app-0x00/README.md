
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