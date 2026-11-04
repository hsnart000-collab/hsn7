# MYLIFE Android V1 — حياتي
Native Android starter project (Kotlin + Jetpack Compose + Room + AlarmManager).

## Included
- Arabic-first RTL Compose interface (dashboard, tasks, add-task dialog)
- Local Room database for tasks
- Scheduled reminders using AlarmManager + notification channel
- No cloud account or network permission
- Dark, clean UI

## Build
Open this folder in Android Studio (Koala or newer), allow Gradle sync, then Run on Android device.
The project uses Android Gradle Plugin 8.7.3, Kotlin 2.0.21, Compose BOM 2024.12.01.
Android 13+ asks for notification permission at runtime.
Exact alarms may require granting "Alarms & reminders" permission in Android settings on Android 12+.
