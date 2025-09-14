# Android / Java / Kotlin
.gradle/
build/
*/build/
local.properties
/.idea/
/captures/
.externalNativeBuild/
.cxx/

# Gradle
.gradle/
build/
!gradle-wrapper.jar
gradle-wrapper.jar

# Kotlin
*.iml
*.kts

# Mac / Windows
.DS_Store
Thumbs.db

# Misc
*.log
/*.keystore
/*.jks

# Android Studio
.idea/
*.iml
out/
````markdown name=README.md
# GiedoFinance (Android app)

This repository contains the Android app "GiedoFinance".

How to import locally:
1. Clone the repo or copy the project folder.
2. Open the folder in Android Studio and let Gradle sync.
3. Build and run on an emulator or device.

Branches:
- add-android-app — branch for the Android app import.

Notes:
- The app requires INTERNET permission for image loading.
- If Gradle wrapper is missing, use Android Studio to generate or install Gradle.
