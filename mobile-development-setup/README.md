# Mobile Development Setup

## Objective
Mobile development requires more computational resources compared to web development. To streamline the process, we use the Expo Framework for React Native, which simplifies app development and testing. This document outlines the setup process for a smooth development experience.

## Prerequisites
Ensure you have the following installed:
- **Node.js LTS** (Latest Long-Term Support version)
- **VS Code** (Recommended IDE)
- **Compatible OS** (macOS, Linux, or Windows)
- **Expo CLI** (Run: `npm install -g expo-cli`)
- **Expo Go App** (For testing on physical devices)

## Why Use Expo Go?
- Avoids the need for hardware-intensive emulators.
- Allows testing on real devices (both iOS and Android).
- Provides seamless development with live reloading.

## Installation Steps for Expo Go
1. Visit [Expo Go Homepage](https://expo.dev/go).
2. Select the latest SDK version.
3. Install the app on your physical device:
   - **Android:** Download from the [Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent).
   - **iOS:** Download from the [Apple App Store](https://apps.apple.com/us/app/expo-go/id982107779).
4. Open Expo Go on your device.
5. Create an account or log in if you already have one.

## Challenges and Troubleshooting
### Common Issues & Fixes
- **Expo Go crashes on launch**: Restart your device and ensure it’s updated.
- **Unable to install Expo Go**: Check device storage and app store availability.
- **Connection issues**: Ensure your device and development machine are on the same Wi-Fi network.
- **Expo CLI not recognized**: Run `npm install -g expo-cli` again and restart your terminal.

## Repository Structure
```
prodev-mobile-setup/
└── mobile-development-setup/
    └── README.md
```

## Next Steps
- Verify the setup by running `npx expo start` in a new project.
- Scan the QR code with Expo Go to test your setup.

This completes the setup process, allowing us to proceed with mobile development using React Native, TypeScript, NativeWindCSS, and Expo.
