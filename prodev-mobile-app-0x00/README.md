# reset-project"

# First Mobile App Setup with Expo Router

## Objective

The goal of this task is to create a first mobile application using the **Expo Router (Tabs) template**, understand the scaffolding process, and explore the basic file structure of a React Native application built with Expo.

This setup enables rapid development and testing using a physical mobile device through Expo Go.

---

## Project Setup

### Scaffolding Steps

1. **Navigated to the Parent Directory**  
   The terminal was opened and navigation was done into the main project directory where the mobile setup is maintained.

2. **Created a New Expo Application**  
   A new Expo project was initialized using the `create-expo-app` command with the **Expo Router (Tabs) template** to enable file-based routing and tab navigation.

3. **Automatic Dependency Installation**  
   During the scaffolding process, npm automatically installed all required dependencies, including React Native, Expo Router, and supporting libraries.

4. **Generated Project Structure**  
   The setup produced a structured Expo project with predefined folders for routing, constants, and assets.

---

## File Structure Overview

The following files and directories are central to this project:

- `app/(tabs)/index.tsx`  
  This file represents the home screen of the application. It is the default route rendered when the app launches.

- `constants/Colors.tsx`  
  This file defines shared color values used across the application for consistent styling.

- `app-example/`  
  This directory contains example application files used to demonstrate the basic Expo Router structure and UI customization.

---

## Home Screen Modification

The default welcome message in the home screen was updated to confirm that the application renders custom changes correctly.

- Original text: `Welcome!`
- Updated text: **First App Created**

This verified that the Expo development environment was working as expected.

---

## Running the Application

The Expo development server was started using the following command:

```bash
npx expo start
