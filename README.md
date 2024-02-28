## Pre-requisite
You should have Expo Go application on your mobile device. It is available in both Google Play Store and App Store

## Local Build

- Clone the project to your local machine
- Install `node_modules`
```bash
npm install
npm install --global eas-cli
```
### In the project directory, you can run:
- Runs the app in the development mode. Open it in the Expo app on your phone to view it.
```bash
npm start
```
- Starts the dev server and tunnels the connection so you can access it anywhere, especially for WSL2.
```bash
npm run tunnel
```
- Runs the app on an Android device or emulator.
```bash
npm run android
```
- Runs the app on an iOS simulator.
```bash
npm run ios
```
- Runs the app in the web browser.
```bash
npm run web
```