# Android App - Kotlin Window

This is a basic Android application written in Kotlin with a simple window (Activity).

## Project Structure

```
app/
├── src/main/
│   ├── java/com/example/app/
│   │   └── MainActivity.kt          # Main Activity (Window)
│   ├── res/
│   │   ├── layout/
│   │   │   └── activity_main.xml    # Main window layout
│   │   └── values/
│   │       └── strings.xml          # String resources
│   └── AndroidManifest.xml          # App manifest
├── build.gradle                     # App-level build configuration
build.gradle                         # Project-level build configuration
settings.gradle                      # Gradle settings
```

## Features

- **MainActivity**: The main window (Activity) of the application
- **UI Layout**: Simple layout with a TextView displaying "Hallo Welt!" (Hello World in German)
- **Kotlin**: Written entirely in Kotlin
- **AndroidX**: Uses modern AndroidX libraries

## Requirements

- Android Studio Arctic Fox or later
- Android SDK 21 or higher (minimum)
- Kotlin 1.8.0

## How to Build

1. Open the project in Android Studio
2. Sync Gradle files
3. Run the app on an emulator or physical device

## Components

### MainActivity.kt
The main Activity class that represents the window of the application. It extends `AppCompatActivity` and sets the content view to the layout defined in `activity_main.xml`.

### activity_main.xml
The layout file that defines the UI of the main window. It uses a ConstraintLayout with a centered TextView.

### AndroidManifest.xml
Defines the app's package name, components, and permissions. Declares MainActivity as the launcher activity.
