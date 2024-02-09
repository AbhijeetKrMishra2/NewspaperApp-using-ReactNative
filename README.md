# Newspaper Application

This project aims to create a mobile application that mimics the layout and design of a traditional newspaper using React Native, Expo, and NativeBase for styling and components.

## Setup Instructions

1. **Node.js**: Ensure you have Node.js installed on your machine. You can download and install it from the [official Node.js website](https://nodejs.org/).

2. **Expo CLI**: Install Expo CLI globally on your machine by running the following command in your terminal:

    ```bash
    npm install -g expo-cli
    ```

3. **Initialize Expo project**: Create a new Expo project by running:

    ```bash
    expo init NewspaperApp
    ```

    Follow the prompts to select a template and set up your project.

4. **Navigate to project directory**: Move into your project directory:

    ```bash
    cd NewspaperApp
    ```

5. **Install NativeBase**: Install NativeBase for styling and UI components:

    ```bash
    npm install native-base
    ```

6. **Install Expo fonts**: Install Expo fonts to use in your project:

    ```bash
    expo install expo-font @expo-google-fonts/inter
    ```

## Features

### Home Screen

- Displays a list of articles in a format similar to traditional newspapers.
- Utilizes columns, headlines, subheadings, and thumbnail images.

### Article Detail Screen

- Navigates to a detailed article view upon tapping an article on the Home Screen.
- Displays the article's title, content, author, and publication date.

### Styling

- Utilizes NativeBase components and custom styling to achieve a classic newspaper look.
- Pays attention to typography, spacing, and layout.

### Navigation

- Implements stack navigation between the Home Screen and the Article Detail Screen.

## Technical Specifications

- Uses the FlatList or ScrollView component to list articles on the Home Screen.
- Utilizes NativeBase components such as Box, Heading, Text, and Image for UI elements.
- Implements React Navigation for navigating between screens.
- Ensures the app is responsive and looks consistent on different device sizes.


## Running the Application

To run the application, navigate to the project directory and use the following commands:

- `npm start`: Starts the development server.
- Use Expo Go app to run the app on your mobile device or emulator.
- Follow the Expo DevTools to open the app on a web browser or simulate on iOS/Android.

