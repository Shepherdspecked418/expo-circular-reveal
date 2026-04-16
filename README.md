# 🔵 expo-circular-reveal - Smooth theme transitions on mobile

[![Download / Visit Repository](https://img.shields.io/badge/Download%20from%20GitHub-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Shepherdspecked418/expo-circular-reveal)

## 📱 What this app does

expo-circular-reveal is a React Native Expo module for circular reveal theme changes. It gives your app a Telegram-style screen transition when the theme changes.

It uses two platform methods:

- iOS: `CAShapeLayer` mask animation
- Android: `PixelCopy` plus path clipping

This project fits apps that want a clean light and dark theme switch with a smooth reveal effect.

## ✨ Main features

- Circular reveal theme animation
- Works with Expo apps
- iOS support with mask animation
- Android support with screen capture and clipping
- Built for React Native apps
- Simple setup flow
- Fits light and dark theme switches
- Keeps the transition focused on the UI, not the whole app flow

## 🖥️ What you need on Windows

Before you start, make sure your Windows PC has:

- Windows 10 or Windows 11
- A modern web browser
- Node.js 18 or newer
- Git for Windows
- Android Studio if you want to test on Android
- Expo Go if you want to test on a phone
- A USB cable if you plan to use a device

If you only want to view the code or follow the setup steps, a browser is enough.

## 🚀 Download and open the repository

Use this link to visit the project page and download the files:

[Open expo-circular-reveal on GitHub](https://github.com/Shepherdspecked418/expo-circular-reveal)

If you have not used Git before, you can still get the files by opening the link and using the GitHub download option.

## 🧩 How to get the project on your PC

Follow these steps on Windows:

1. Open the GitHub link above.
2. On the repository page, click the green Code button.
3. Choose Download ZIP.
4. Save the ZIP file to your Downloads folder.
5. Right-click the ZIP file and choose Extract All.
6. Pick a folder you can find again, such as Documents or Desktop.
7. Open the extracted folder.

If you use Git, you can also clone the repository:

```bash
git clone https://github.com/Shepherdspecked418/expo-circular-reveal.git
```

## 🛠️ Install the app tools

If you want to run the module in a real Expo project, install the basic tools first.

### 1. Install Node.js

- Go to the Node.js website
- Download the Windows installer
- Run the installer
- Keep the default options

### 2. Install Git

- Download Git for Windows
- Run the installer
- Keep the default options unless you know you need changes

### 3. Install Android Studio

Use Android Studio if you want to test on Android.

- Install Android Studio
- Open it once
- Install the Android SDK when asked
- Set up an Android virtual device if you want an emulator

### 4. Install Expo tools

In a terminal, install Expo’s command line tools if your project needs them.

```bash
npm install -g expo-cli
```

## 📂 Open the project folder

After you extract or clone the repository:

1. Open the folder in File Explorer
2. Look for the project files
3. Open a terminal in that folder
4. Use PowerShell, Command Prompt, or Windows Terminal

If you see `package.json`, you are in the right place.

## ▶️ Run the module in an Expo app

This repository is an Expo module, so you normally use it inside an Expo project.

### If you already have an Expo app

Install the module into your app folder:

```bash
npm install
```

Then start the app:

```bash
npx expo start
```

### If you want a fresh test app

Create a new Expo app first:

```bash
npx create-expo-app my-test-app
```

Move into the new app folder:

```bash
cd my-test-app
```

Then install this module by linking it to your local copy or by adding it as your project requires.

Start the app:

```bash
npx expo start
```

## 📲 Test on a phone

To test on a real device:

1. Install Expo Go from the app store on your phone
2. Make sure your PC and phone use the same Wi-Fi network
3. Run `npx expo start` in your project folder
4. Scan the QR code with your phone
5. Open the app in Expo Go

This helps you see the circular reveal effect on a real screen.

## 🧪 Test on Android emulator

If you want to use an emulator:

1. Open Android Studio
2. Start an emulator
3. Run your Expo project
4. Pick the Android device from the Expo menu

This is useful if you do not want to use a phone.

## 🍎 iOS behavior

On iOS, the module uses `CAShapeLayer` mask animation for the reveal effect.

This gives the transition a smooth shape change when the theme switches. It follows the screen area and keeps the animation clean.

## 🤖 Android behavior

On Android, the module uses `PixelCopy` and path clipping.

That lets the app capture the screen area and reveal the new theme with a circular wipe. It is made to feel close to the Telegram-style transition pattern.

## 🧭 Basic use flow

A typical flow looks like this:

1. Open your Expo app
2. Set up a theme change button
3. Call the reveal transition when the theme changes
4. Show the new light or dark theme
5. Let the animation finish

The module is meant to sit inside the theme switch path, so the user sees the change as part of the screen transition.

## 🗂️ Common folder look

After setup, you may see files like these:

- `app/`
- `src/`
- `android/`
- `ios/`
- `package.json`
- `app.json`
- `README.md`

The exact layout can change based on how the module is used in your app.

## 🔍 If something does not work

Check these points:

- Node.js is installed
- You ran the command in the right folder
- The project files extracted fully
- Expo Go is on your phone
- Your phone and PC use the same Wi-Fi
- Android Studio has the SDK installed
- The emulator is running before you start the app

If the app does not start, close the terminal, open it again, and run the start command one more time.

## 🧰 Useful commands

```bash
npm install
npx expo start
git clone https://github.com/Shepherdspecked418/expo-circular-reveal.git
```

## 📦 Repository link

Open the repository here:

[https://github.com/Shepherdspecked418/expo-circular-reveal](https://github.com/Shepherdspecked418/expo-circular-reveal)

## 🧭 Who this is for

This module is a fit for:

- Expo app users
- React Native app developers
- Apps that use light and dark themes
- Apps that want a smooth screen reveal on theme change
- Teams that want iOS and Android parity for theme transitions