# flutter_auth

An example of an app with Instagram Authentication on Flutter.

# Installation and Usage
1. Follow the installation instructions on https://flutter.io/get-started/install/ to install Flutter.
    * System requirements
        * Operating System of 64 bit (Windows, MacOs, Linux)
        * Disk Space: Windows - 400 MB, MacOs - 700 MB, Linux - 600 MB
        * Tools: Windows (git), MacOs-Linux (bash, mkdir, rm, git, curl, unzip, which)
    * Get the Flutter SDK
To get Flutter, use git to clone this [repository](https://github.com/flutter/flutter) and then add the flutter tool (path\to\flutter\bin) to your computer path.
    * run "flutter doctor" on command prompt or POWER SHELL.
    Running flutter doctor shows any remaining dependencies you may need to install.
    * iOS setup
        - Install Xcode
        - Set up the iOS simulator
        - if you want to deploy to iOs devices you need to intall these dependencies:
    homebrew, libimobiledevice, ideviceinstaller, ios-deploy, cocoapods
    * Android setup 
        - Install Android Studio, IntelliJ or Visual Studio Code
        - Dependencies: Flutter and Dart plugins (Android Studio, IntelliJ) - dart code Extension (Visual Studio Code)
        - Set up your Android device or emulator
2. Clone this repository
3. You'll need to create an Instagram developer account. Follow the instructions [here](https://www.instagram.com/developer/).
4. Once your account is created, you'll register your application and obtain your APP ID and APP SECRET.
  - Configure your redirect URI to: http://localhost:8585
5. Put your APP_ID and APP_SECRET in the constants.dart file.
5. flutter_auth can be run like any other Flutter app, either through the IntelliJ UI or
    through running the following command from within the flutter_auth directory:
```
flutter run
```

