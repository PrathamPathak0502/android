Android Application README
Overview
This Android application is designed to provide an interactive user interface for various functionalities, such as user login, registration, and access to different activities. The app includes a splash screen, login and registration screens, as well as several main activities that users can navigate between.

Features
Splash Screen: Displays when the app is launched.
Login Screen: Allows users to sign in using their credentials.
Registration Screen: Provides users the ability to create a new account.
Main Activities: Includes multiple main screens (MainActivity, MainActivity2, MainActivity3) where different app content is displayed.
Android Manifest
The Android manifest (AndroidManifest.xml) outlines the structure and permissions required for the app. Key components of the manifest:

Permissions:

INTERNET: Allows the app to access the internet.
Application Configuration:

allowBackup: Enables backup of app data.
dataExtractionRules and fullBackupContent: These XML files define rules for data extraction and backup configurations.
icon: Defines the app's icon.
theme: Specifies the app's visual style (Theme.CricBuzz).
supportsRtl: Enables right-to-left text support for different languages.
Activities:

SplashScreen: The launcher activity, marked as android.intent.action.MAIN and android.intent.category.LAUNCHER.
Login: User login screen for authentication.
Register: User registration screen for account creation.
MainActivity, MainActivity2, MainActivity3: Different main activities that represent various views and functionalities of the app.
Exported:

Set to true for activities that need to be accessible by other apps or components. Activities like SplashScreen and MainActivity are exported.
Set to false for activities that should not be accessible outside the app (Login, Register, etc.).
Setup and Usage
Clone or download the project to your local machine.
Open the project in Android Studio.
Build and run the app on an emulator or connected Android device.
Application Flow
Upon launching the app, the SplashScreen is shown, which transitions to either the Login or MainActivity depending on the user’s session status or navigation path.
MainActivity serves as the primary entry point to the app's core features, with additional screens like MainActivity2 and MainActivity3 available for different functionalities.
Users can register a new account via the Register screen, and authenticate through the Login screen.
Dependencies
Android API Level 31
Required permissions for internet access.
