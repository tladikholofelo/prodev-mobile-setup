# First Mobile App with Expo Router

## Project Setup

### 1. Setting Up the Project

To create the project, we ran:

```sh
npx create-expo-app@latest .
```

This command generated the basic structure of a React Native app with Expo.

### 2. Modifying the Home Screen

- Edited `app/(tabs)/index.tsx`
- Changed default text `"Welcome!"` to `"** First App Created **"`

### 3. Running the Application

- Started the app with:

```sh
npx expo start
```

- Scanned the QR code with Expo Go for testing.

### 4. Resetting the Project

- Ran `npm run reset-project`
- This removed cached files, `node_modules`, and dependencies.
- Reinstalled dependencies with:

```sh
npm install
```

### Observations:

- Resetting ensures a clean environment.
- Helps resolve dependency issues in case of conflicts.

