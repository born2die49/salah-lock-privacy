# Privacy Policy for Salah Lock

**Effective Date:** February 20, 2026

Welcome to Salah Lock. This Privacy Policy explains how we collect, use, process, and safeguard your information when you use the Salah Lock mobile application ("the App").

Salah Lock is built with a "privacy-first, local-first" philosophy. Our core functionality relies on processing data directly on your device. We do not collect, sell, or share your personal data with third parties for marketing or advertising purposes.

Please read this Privacy Policy carefully to understand our practices regarding your data.

## 1. Information We Collect and How We Use It

To provide our core distraction management and prayer accountability features, Salah Lock requires specific Android permissions. Here is exactly how we use them:

### A. Accessibility Service API Usage

Salah Lock utilizes the Android Accessibility Service API to provide its core "App Lock" and "Focus Mode" functionality during active prayer times.

* **What we access:** We use this service strictly to detect the package name (Application ID) of the app currently open on your screen to determine if it matches your personal "Blocked Apps" list.
* **What we DO NOT access:** We do not read, record, or store any of your screen content, text inputs, messages, or passwords.
* **Data Processing:** This foreground application check is processed entirely locally on your device in real-time. It is never transmitted to our servers or shared with any third parties.

### B. Installed Applications Inventory (`QUERY_ALL_PACKAGES`)

To allow you to select which applications to restrict during prayer times, Salah Lock requests permission to retrieve a list of installed apps on your device.

* **Usage:** This list is only used to populate the in-app selection screen so you can choose which apps to block or allow.
* **Data Processing:** Your list of installed applications is stored locally on your device. It is never transmitted off your device or shared with anyone.

### C. Location Data

Salah Lock requires access to your device's precise or approximate location (`ACCESS_FINE_LOCATION` or `ACCESS_COARSE_LOCATION`) to accurately calculate astronomical prayer times based on your geographical coordinates.

* **Usage:** Your coordinates are processed locally to fetch and generate daily prayer schedules.
* **Data Processing:** We do not track your location history or send your location to external remote servers.

### D. Prayer Statistics

To provide you with insights and a "Heatmap" of your prayer habits, Salah Lock processes your prayer completion history.

* **Data Processing:** All statistical data, streaks, and focus metrics are stored securely within your device's local database (Room Database). No personal usage data is sent to the cloud.

## 2. Third-Party Services and Telemetry

While your personal data remains on your device, we use a third-party service solely to ensure the App runs smoothly:

* **Google Firebase Crashlytics:** We use Crashlytics to monitor the App's stability. If the App crashes, anonymous diagnostic data (such as your device model, operating system version, and the line of code that failed) is sent to Firebase to help us fix the issue. This data does not contain personally identifiable information.

## 3. Data Storage and Security

* **Local Storage:** All of your preferences, blocked app lists, prayer configurations, and spiritual statistics are stored locally on your device.
* **Security:** We rely on the Android operating system's built-in application sandboxing and data encryption to keep your local data secure.
* **Data Deletion:** Because your data is stored locally, you have full control over it. You can permanently delete all your Salah Lock data at any time by clearing the App's data in your Android device settings or by uninstalling the App.

## 4. Background Services and Alarms

To ensure you receive timely prayer interventions, Salah Lock utilizes persistent background services (`FOREGROUND_SERVICE`) and exact alarms (`SCHEDULE_EXACT_ALARM`). These operate purely to monitor the time and trigger local notifications or overlays when a prayer window begins. They do not transmit data in the background.

## 5. Children's Privacy

Salah Lock is designed for general audiences. We do not knowingly collect personal information from children under the age of 13. Because the App operates locally and does not transmit personal data, it inherently complies with children's privacy principles.

## 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time to reflect changes in our practices or Android operating system requirements. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. You are advised to review this Privacy Policy periodically for any changes.

## 7. Contact Us

If you have any questions, concerns, or suggestions regarding this Privacy Policy or our data practices, please contact us at:

* **Email:** [jamisays@gmail.com](mailto:jamisays@gmail.com)
