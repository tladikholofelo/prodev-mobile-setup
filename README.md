# ProDev Mobile Setup

This repository contains React Native projects built with Expo, implementing various UI components and features to enhance mobile development skills.  

## Projects Overview

### 1. prodev-mobile-app-0x00: Create Your First Mobile App

#### Objective:

Set up a React Native project using the Expo Router template and modify the home screen.  

#### Steps:
1. Navigate to the project directory:  

   ```sh
   cd prodev-mobile-setup
   ```

2. Initialize a new Expo project:  

   ```sh
   npx create-expo-app@latest .
   ```

3. Modify the home screen:  
   - Open `app/(tabs)/index.tsx`
   - Change `"Welcome!"` to `"First App Created"`.  

4. Run the application:  

   ```sh
   npx expo start
   ```

5. Reset the project and observe changes:  

   ```sh
   npm run reset-project
   ```

#### Observations After Reset:

- The reset removes all dependencies and restores the default project structure.  
- Any changes made to files are lost unless committed to version control.  

### 2. prodev-mobile-app-0x01: Implementing Mobile Components

#### Objective:

Work with core React Native components and styling using `View`, `Text`, and `StyleSheet`.  

#### Steps:

1. Initialize a new Expo project:  

   ```sh
   npx create-expo-app@latest prodev-mobile-app-0x01
   ```

2. Reset the project:  

   ```sh
   npm run reset-project
   ```

3. Modify `app/index.tsx`:  
   - Change the main `<Text>` component to `"Entry Screen - Awesome"`.  
   - Replace inline styles with `style={styles.container}`.  
   - Add additional `<Text>` components with different styles.  

4. Define styles in `StyleSheet`.  

5. Run the project with:  
   ```sh
   npx expo start
   ```

### 3. prodev-mobile-app-0x02: Safe Areas, Images, and Touchable Components

#### Objective:

Implement `SafeAreaView`, `Image`, `ImageBackground`, `TouchableOpacity`, and responsive layouts.  

#### Steps:

1. Initialize and reset the project:  

   ```sh
   npx create-expo-app@latest prodev-mobile-app-0x02
   npm run reset-project
   ```

2. Move assets (`Logo.png`, `background-image.png`) to `assets/images`.  

3. Modify `app/index.tsx`:  
   - Wrap the app in `SafeAreaProvider` and `SafeAreaView`.  
   - Set a full-screen background image using `ImageBackground`.  
   - Add a centered logo image using `Image`.  
   - Insert styled text and buttons (`TouchableOpacity`).  
   - Add a "Continue to home" navigation prompt.  

4. Apply styles to ensure proper UI layout.  

5. Run the project:  

   ```sh
   npx expo start
   ```

### 4. prodev-mobile-app-0x03: Explore More Core Components

#### Objective:

Implement additional React Native core components and styling to build a login screen.  

#### Steps:

1. Create a new Expo app:  

   ```sh
   npx create-expo-app@latest prodev-mobile-app-0x03
   ```

2. Navigate into the project:  

   ```sh
   cd prodev-mobile-app-0x03
   ```

3. Reset the project:  

   ```sh
   npm run reset-project
   ```

4. Download assets (`logo.png`, `google.png`, `facebook.png`, `splash.png`) and place them in `assets/images`.  

5. Implement styles in `styles/index.tsx`.  

6. Modify `app/_layout.tsx` to hide the header.  

7. Update `app/index.tsx` to:  
   - Add a navigation bar with a back icon and logo.  
   - Implement email/password input fields.  
   - Include a sign-in button and social media authentication buttons.  
   - Add a "Join now" prompt.  

8. Run the application:  

   ```sh
   npx expo start
   ```

## Technologies Used

- **React Native** (Expo framework)  
- **TypeScript**  
- **Expo Router**  
- **React Native Safe Area Context**  
- **React Native Components (View, Text, Image, TouchableOpacity, TextInput, etc.)**  

## Project Structure

```
prodev-mobile-setup/
│── prodev-mobile-app-0x00/
│── prodev-mobile-app-0x01/
│── prodev-mobile-app-0x02/
│── prodev-mobile-app-0x03/
│   ├── app/
│   │   ├── _layout.tsx
│   │   ├── index.tsx
│   ├── styles/
│   │   ├── index.tsx
│   ├── assets/images/
│   │   ├── logo.png
│   │   ├── google.png
│   │   ├── facebook.png
│   │   ├── background-image.png
│── README.md
```

## How to Run Any Project

1. Clone the repository:  

   ```sh
   git clone https://github.com/YOUR_GITHUB_USERNAME/prodev-mobile-setup.git
   cd prodev-mobile-setup
   ```

2. Navigate to the project folder:  

   ```sh
   cd prodev-mobile-app-0x0X  # Replace X with the desired project number
   ```

3. Install dependencies:  

   ```sh
   npm install
   ```

4. Start the application:  

   ```sh
   npx expo start
   ```
