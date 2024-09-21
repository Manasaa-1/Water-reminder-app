# Water Reminder App

The **Water Reminder App** is a mobile application designed to help users stay hydrated by sending regular notifications to drink water. The app is developed using Android Studio and follows a **Mobile Management System** for handling user preferences, reminders, and notification management.

## Features

- **Personalized Water Intake Goals**: Users can set daily water intake goals based on their weight, activity level, and climate conditions.
- **Notification Reminders**: The app sends push notifications to remind users to drink water at regular intervals.
- **Customizable Reminder Intervals**: Users can adjust the frequency and timing of the water reminders according to their preference.
- **Water Intake Logging**: Users can log their water intake throughout the day and track progress towards their daily goal.
- **History and Statistics**: The app provides a history of water intake with visual charts and statistics to monitor hydration habits over time.
- **Mobile Management System**: The app utilizes a robust system to manage user settings, notifications, and data storage.

## Technologies Used

- **Android Studio**: The primary development environment for building the app.
- **Java/Kotlin**: Core programming languages used for Android development.
- **SQLite**: Embedded database for storing user preferences and water intake history locally on the device.
- **Android Notifications**: Integrated Android notifications API to send timely reminders to users.

## How the App Works

1. **User Registration**: Users can input their personal details, such as weight, activity level, and water intake goals, which the app uses to calculate the ideal daily water intake.
2. **Reminder Setup**: The app allows users to set custom reminders at preferred intervals, ensuring timely notifications to drink water.
3. **Notifications**: The app utilizes Android's notification system to send reminders even when the app is running in the background.
4. **Tracking Progress**: Users can log their water intake, and the app will calculate and display their progress toward the daily goal.
5. **Data Management**: All user data, including preferences and intake history, is stored in a local SQLite database for easy access and tracking.

## Key Features of the Mobile Management System

- **User Preferences Management**: Handles the storage and retrieval of user preferences like water intake goals and reminder intervals.
- **Notification Management**: Utilizes the Android `AlarmManager` and `NotificationManager` to trigger reminders.
- **Data Persistence**: Uses SQLite to maintain a local database of water intake history and user settings, ensuring data is saved even when the app is closed.

## Future Enhancements

- **Sync with Wearable Devices**: Integration with smartwatches and fitness bands to track water intake and display reminders.
- **Cloud Backup**: Implement cloud storage options to back up user data and allow for syncing across multiple devices.
- **Social Features**: Add social sharing options to let users share their hydration achievements with friends.
- **Dark Mode**: Provide a dark theme option for users who prefer a darker interface.

## License
This project is licensed under the MIT License.
