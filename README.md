# Day11_31_12_2024
# MyApp

## Overview
This project is a React Native application built with Expo and React Navigation. The app consists of three primary screens:

- **Home Screen**: Displays general information with navigation options.
- **About Us Screen**: Provides historical details about the University of Vavuniya.
- **Contact Us Screen**: Allows users to input contact details and send messages.

## Features

- **Navigation**: Seamless navigation between screens using React Navigation.
- **Styling**: Custom styles using `StyleSheet` to ensure a consistent and responsive design.
- **Forms**: Input fields for contact details on the Contact Us screen.
- **Keyboard Handling**: Ensures proper UI behavior on different platforms with `KeyboardAvoidingView`.
- **Responsive Layout**: Scrollable content with `ScrollView`.

## File Structure
```
MyApp/
├── assets/
│   └── uovlogo.png        # University logo used in About Us screen
├── components/
│   └── AboutUs.js         # About Us screen component
│   └── ContactUs.js       # Contact Us screen component
│   └── Home.js            # Home screen component
├── App.js                 # Entry point of the application
└── README.md              # Documentation
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/MyApp.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MyApp
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

## Running the Application

1. Start the development server:
   ```bash
   npm start
   ```
2. Use the Expo Go app to scan the QR code or run the app on an emulator/simulator:
   ```bash
   npm run android    # For Android emulator
   npm run ios        # For iOS simulator
   ```

## Screens

### Home Screen
- Displays introductory text and two navigation buttons:
  - Navigate to **Contact Us** screen.
  - Navigate to **About Us** screen.

### About Us Screen
- Displays detailed historical information about the University of Vavuniya.
- Includes:
  - A header with the title "History".
  - University logo.
  - A detailed paragraph about the university's establishment and faculties.

### Contact Us Screen
- Provides a form to input contact details:
  - Name
  - Email
  - Phone number
  - Message
- A submit button that navigates to the About Us screen.

## Technologies Used

- **React Native**: Framework for building native apps.
- **React Navigation**: Navigation library for handling routes.
- **React Native Paper**: UI components for React Native.
- **Expo**: Toolchain for developing React Native apps.

## Dependencies

- `react-native`
- `@react-navigation/native`
- `@react-navigation/stack`
- `react-native-paper`
- `expo`

## Styles

- Consistent styling using `StyleSheet`.
- Responsive layouts with `ScrollView` and `KeyboardAvoidingView`.
- Flexbox for alignment and spacing.


