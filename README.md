# TimeeApp (SBTimer)

TimeeApp is a versatile period-based timer application built with Jetpack Compose. It is designed for timing sports, games, or any activities that require multiple periods with optional overtime.

## Features

- **Configurable Periods**: Set the number of periods (e.g., 1, 2, or 3).
- **Customizable Length**: Choose from common period lengths (10, 15, or 20 minutes).
- **Overtime Support**: Toggle an optional overtime period with its own configurable length.
- **Manual Time Editing**: Tap the timer while paused to manually adjust minutes and seconds.
- **State Persistence**: The timer state and settings are saved automatically, allowing you to resume exactly where you left off even if the app is closed.
- **Visual Alerts**: The timer display blinks when a period ends to provide clear visual feedback.
- **Bilingual Support**: Fully localized in both English and Finnish.
- **Modern UI**: Built using Material Design 3 and Jetpack Compose for a clean, responsive experience.

## Technical Details

- **Language**: Kotlin
- **UI Framework**: Jetpack Compose
- **Architecture**: MVVM (Model-View-ViewModel)
- **Data Persistence**: SharedPreferences for lightweight storage of timer state and user preferences.

## Getting Started

1. Clone the repository.
2. Open the project in Android Studio.
3. Build and run the `:SBTimer` module on an Android device or emulator.

## Usage

- **Start/Stop**: Use the main button at the bottom to control the timer.
- **Reset**: Use the refresh icon in the top bar to reset the timer to zero.
- **Settings**: Access the gear icon in the top bar to change the number of periods, period length, overtime settings, and language.
- **Edit Time**: When the timer is stopped, tap the time display to manually set a specific time.
