# Wallpaper App (React Native) ✨

Welcome to the **Wallpaper App**\! This is a fresh React Native project, built using the `@react-native-community/cli`. Get ready to explore a beautiful world of wallpapers on your mobile device\!

-----

## Getting Started 🚀

Before you dive in, please ensure your development environment is properly set up. It's a crucial first step for a smooth experience\!

  * **Set Up Your Environment:** Follow the official [React Native environment setup guide](https://reactnative.dev/docs/set-up-your-environment) to get everything configured.

### Step 1: Start the Development Server (Metro)

First, we need to kick off **Metro**, the JavaScript build tool for React Native. This server compiles your code and serves it to your app.

From the root of this project, run one of these commands in your terminal:

```sh
# Using npm
npm start

# OR using Yarn
yarn start
```

### Step 2: Run Your App on a Device or Simulator

With Metro running in a separate terminal, open a **new terminal window** from the project's root. Now you can build and launch the app on your desired platform.

#### For Android 🤖

```sh
# Using npm
npm run android

# OR using Yarn
yarn android
```

#### For iOS 🍎

For iOS, you'll need to install CocoaPods dependencies. This is typically a one-time setup or when native dependencies are updated.

1.  **First-time CocoaPods setup:**
    ```sh
    bundle install
    ```
2.  **Install or update native dependencies:**
    ```sh
    bundle exec pod install
    ```
    (Need more info on CocoaPods? Check out their [Getting Started guide](https://guides.cocoapods.org/using/getting-started.html).)

Then, run your iOS app:

```sh
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

If everything is configured correctly, your new Wallpaper App should now be running beautifully in the Android Emulator, iOS Simulator, or on your connected physical device\! You can also build directly from Android Studio or Xcode if you prefer.

-----

## Making Changes (and seeing them instantly\!) ✨

Now that your app is up and running, let's make it your own\!

Open `App.tsx` in your favorite code editor and start making changes. Thanks to **Fast Refresh**, your app will automatically update as you save, reflecting your modifications instantly.

Need to do a full reload (e.g., to reset the app's state)? Here's how:

  * **Android**: Double-tap the \<kbd\>R\</kbd\> key, or open the **Dev Menu** (\<kbd\>Ctrl\</kbd\> + \<kbd\>M\</kbd\> on Windows/Linux or \<kbd\>Cmd ⌘\</kbd\> + \<kbd\>M\</kbd\> on macOS) and select "Reload".
  * **iOS**: Simply press \<kbd\>R\</kbd\> in the iOS Simulator.

-----

## Congratulations\! 🎉

You've successfully run and modified your React Native Wallpaper App. You're officially a React Native developer\!

### What's Next?

  * **Integrating into an existing app?** Check out the [Integration guide](https://reactnative.dev/docs/integration-with-existing-apps).
  * **Curious to learn more about React Native?** Dive into the comprehensive [documentation](https://reactnative.dev/docs/getting-started).

-----

## Troubleshooting 🐛

If you encounter any issues while getting set up, don't worry\! The official [React Native Troubleshooting page](https://reactnative.dev/docs/troubleshooting) is an excellent resource to help you out.
