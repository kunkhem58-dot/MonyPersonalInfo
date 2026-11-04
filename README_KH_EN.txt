PERSONAL INFORMATION SYSTEM - ANDROID SOURCE PROJECT

Username:
- Monytest

IMPORTANT FIRST RUN:
- Open the app. It will ask you to create a password privately on the phone.
- The password shared in chat is intentionally NOT embedded in the app or source files.
- Use a new password that you do not use on other services.

FEATURES IN THIS STARTER:
- Khmer + English labels
- Local/offline records stored in SQLite
- Search by name or ID
- Add, update, delete records
- Login and change password
- Your supplied portrait is used as the app icon

OPEN / BUILD:
1. Install Android Studio on a Windows, Mac or Linux computer.
2. Open this extracted folder in Android Studio.
3. Allow Gradle sync to finish.
4. Connect an Android phone with USB debugging enabled, or create an emulator.
5. Press Run to install the app.
6. To create an APK: Build > Build Bundle(s) / APK(s) > Build APK(s).

SYNC LIMITATION:
This source currently provides offline/local storage only. Multi-phone online sync is NOT enabled yet.
To add safe sync, a Firebase project (or another backend), authentication rules, encryption in transit,
conflict handling and backup policy must be configured. Do not put real national ID data into a
shared cloud database until access permissions and data-protection requirements are reviewed.

PRIVACY:
- Records are stored locally in the app's SQLite database.
- Android app data is sandboxed, but this starter does not encrypt the database.
- Use only information you are authorized to collect and keep the phone locked.
- Do not share exported database files.
