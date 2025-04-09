# Authapp

Authapp is a Firebase Authentication-based application built using **Next.js** for the web and **React Native with Expo** for the mobile frontend. It allows users to sign in using their **Google account** and supports **push notifications** through Firebase Cloud Messaging (FCM).

---

## Live Web App

To access the web version of the app, open:

```
http://192.16X.XX.XX:3000
```

> Replace this IP with your **actual local IP** or deploy it online (e.g., Vercel or Netlify) to make it accessible remotely.

---

##Mobile App (Expo)

The mobile app is built with **Expo** and embeds the web app using `react-native-webview`.

### Run on Android:

1. Install Expo Go from the Play Store.
2. Clone this repo:
   ```bash
   git clone https://github.com/DurraniAdil/Authapp.git
   cd Authapp
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the app:
   ```bash
   npx expo start --dev-client
   ```
5. Scan the QR code with Expo Go or run it on an emulator.


## Features

-  Google Authentication with Firebase
-  WebView-based mobile integration
-  Firebase Cloud Messaging (Push Notifications)
-  Cross-platform UI using React Native + Expo
-  Fast and responsive design

---

## Tech Stack

- [Next.js](https://nextjs.org/)
- [Firebase Auth](https://firebase.google.com/docs/auth)
- [Firebase Messaging](https://firebase.google.com/docs/cloud-messaging)
- [Expo + React Native](https://expo.dev/)
- [React Native WebView](https://github.com/react-native-webview/react-native-webview)

---

## Development Setup

### 1. Clone the repository:

```bash
git clone https://github.com/DurraniAdil/Authapp.git
cd Authapp
```

### 2. Install dependencies:

```bash
npm install
```

### 3. Run the Web App (Next.js):

```bash
npm run dev
```

> This will start the app at `http://localhost:3000` or your local IP.

### 4. Run the Mobile App (Expo):

```bash
npx expo start --dev-client
```


## Push Notifications Setup (Optional)

Make sure you:
- Configure Firebase FCM in your project.
- Use your `firebase-messaging-sw.js` for web push.
- Enable FCM in your native app with `@react-native-firebase/messaging`.



## Author

Made for an assingment submission by **[@DurraniAdil](https://github.com/DurraniAdil)**
```
