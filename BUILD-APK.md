# Getting the APK (no commands needed)

0. In your repository, create a branch named `zeenath` (the build only runs on that branch).
1. Open the `zeenath` branch and upload ALL files of this project (drag the whole folder contents in, including the hidden `.github` and the `signing` folders). Commit.
2. Open the **Actions** tab. The build starts by itself (about 5 to 8 minutes). Wait for the green tick.
3. Open **Releases** (right side of the repository page) and download the newest `Zeenath-Shameena-Quran-v*.apk`.
4. On your phone: install it. On first launch tap **Allow and continue**.

Every build uses the same signing key (`signing/debug.keystore`), so a new APK installs over the old one and keeps your data. Only the very first install after switching to this version needs the old app to be uninstalled.

## What the Android app does
- Real Android alarms for every prayer (before, at and after) for the next 30 days, with the adhan at prayer time. They work when the app is closed and after a restart.
- Action buttons on notifications: "I prayed" and "Remind in 10 min".
- Rich notifications: next prayer time, Jumu'ah greeting on Fridays, large icon.
- Optional: morning and evening adhkar, Friday Al-Kahf, Monday and Thursday fast reminders.
- A reminder to open the app before the scheduled alerts run out, and a "Refresh alerts" button.
- Branded launch screen, location permission, exact-alarm permission.

## Local build (optional)
Double-click `build-apk.bat` (Windows). Needs Node 20 and Android Studio.
