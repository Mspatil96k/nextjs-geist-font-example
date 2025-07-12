# Android File Share App - Setup and Launch on macOS

This guide provides step-by-step instructions to set up the Android development environment on macOS, import the project, and launch the app on a device or emulator.

## 1. Install Android Studio

1. Go to the [Android Studio download page](https://developer.android.com/studio).
2. Download the macOS version of Android Studio.
3. Open the downloaded `.dmg` file and drag Android Studio to the Applications folder.
4. Launch Android Studio from Applications.

## 2. Set Up Android SDK and Tools

1. On first launch, Android Studio will prompt to install SDK components. Follow the prompts to install the latest Android SDK, SDK Platform, and Android Virtual Device (AVD) tools.
2. Open **Preferences** (Android Studio > Preferences).
3. Navigate to **Appearance & Behavior > System Settings > Android SDK**.
4. Ensure the latest SDK platforms and tools are installed.

## 3. Connect a Physical Device (Optional)

1. Enable **Developer Options** on your Android device:
   - Go to **Settings > About phone**.
   - Tap **Build number** seven times until developer mode is enabled.
2. Enable **USB Debugging** in **Developer Options**.
3. Connect your device to your Mac via USB.
4. Allow USB debugging authorization on your device when prompted.

## 4. Import the Project

1. Open Android Studio.
2. Click **Open an existing Android Studio project**.
3. Navigate to the `android-file-share-app` directory and select it.
4. Wait for Gradle to sync and build the project.

## 5. Run the App

### Using an Emulator

1. Open **AVD Manager** (Tools > AVD Manager).
2. Create a new virtual device or select an existing one.
3. Start the emulator.
4. Click the **Run** button (green triangle) in Android Studio.
5. Select the emulator as the target device.

### Using a Physical Device

1. Ensure your device is connected and recognized by Android Studio.
2. Click the **Run** button.
3. Select your device as the target.

## 6. Grant Permissions

- The app requires permissions for location, Bluetooth, and storage.
- When running the app, grant the requested permissions on the device/emulator.

## 7. Debugging and Logs

- Use **Logcat** in Android Studio to view logs and debug messages.
- Use breakpoints and the debugger for step-by-step debugging.

## Additional Resources

- [Android Developer Documentation](https://developer.android.com/docs)
- [WiFi Direct API Guide](https://developer.android.com/guide/topics/connectivity/wifip2p)
- [Bluetooth API Guide](https://developer.android.com/guide/topics/connectivity/bluetooth)

---

This completes the setup and launch guide for the Android File Share App on macOS.
