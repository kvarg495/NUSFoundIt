# NUSFoundIt

Welcome to NUSFoundIt! This is a [React Native](https://reactnative.dev/) project created by Kevin Varghese and Advait Phadnis for CP2106 *Orbital* at NUS. It runs natively on [Expo Go](https://expo.dev) but its production web deployment can also be accessed on [Vercel](https://vercel.com) (which *only* works on **mobile web browsers**). 
***
NUSFoundIt is a centralized, smart lost-and-found mobile utility designed exclusively for National University of Singapore (NUS) students and staff. The app aims to replace fragmented campus Telegram channels and outdated SharePoint listings with a secure, verified digital ecosystem. 

Students can log lost or found items with photo uploads and campus venue tags derived from NUSMods data into the app. It features a custom set-theoretic matching engine that scores potential item matches based on shared keywords, categories, location proximity, and timestamps, utilising Firebase Cloud Functions to trigger automated Telegram push alerts when high-confidence matches are found.

## View on Expo Go

### Prerequisites
Before setting up, users/testers must ensure the following is installed on their computer:
- Node.js --> Version 20.x or 22.x LTS recommended
- Git --> for cloning of repository
- Expo Go App --> A compatible release is crucial, specifically SDK 55.x.x. Android users can download the .apk file directly from the [website](http://expo.dev/go), specifically choosing the SDK 55 release. iOS users can install the Expo Go SDK 55 beta through Apple TestFlight. First, install the TestFlight app from the App Store. Then, join the Expo Go beta using this [link](https://testflight.apple.com/join/GZJxxfUU).

### Installation and Execution
1. Clone the project by opening terminal/PowerShell and running the following command:

   ```bash
   git clone https://github.com/advaitio/NUSFoundIt.git
   ```
   ```bash
   cd NUSFoundIt
   ```

2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the local server:

   ```bash
   npx expo start -c
   ```

### Viewing
1. Connect your smartphone to the same WiFi network as the computer hosting the server. 
2. Open the Expo Go app and tap “Scan QR Code” to scan the provided QR image in the terminal. The app will launch NUSFoundIt instantly. 

## Vercel Web Deployment
A dedicated production web deployment can be accessed on Vercel [directly](https://nus-found-it.vercel.app/) or by scanning the QR code provided below.

![Vercel Web Deployment QR Code](/assets/images/vercel-qr-code.png)

## Documentation
For a comprehensive overview of the project, including system architecture, full feature documentation, and extensive testing, please refer to our [official project documentation](https://docs.google.com/document/d/1v8p8_UQTsjjsMEdLEcX-BPVSjyjZ8ZbgtYQxaLvzstQ/edit?usp=sharing). 