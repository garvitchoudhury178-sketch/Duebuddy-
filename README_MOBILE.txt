DUEBUDDY ANDROID APK PROJECT

This is an Android WebView wrapper around the DueBuddy prototype.

IMPORTANT: This ZIP is an Android project, not a compiled APK. The current workspace does not have the Android SDK/Gradle build environment needed to compile and sign an APK locally.

BUILD FROM YOUR PHONE USING GITHUB ACTIONS:
1. Extract this ZIP.
2. Create a GitHub repository called duebuddy-android.
3. Upload all files and folders from this ZIP into the repository root (including the .github folder).
4. Open the repository's Actions tab.
5. If asked, enable GitHub Actions.
6. Choose "Build DueBuddy APK" and tap Run workflow (or push the files to main to trigger it).
7. Wait for the workflow to finish successfully.
8. Open that completed workflow run, scroll to Artifacts, and download DueBuddy-debug-APK.
9. Extract the artifact ZIP; it contains app-debug.apk.
10. Install the APK on your Android phone. Android may ask you to allow installation from that browser/file manager.

CURRENT FEATURES:
- Local borrower list, amounts, dates, partial payments
- Light/dark mode
- Hindi/Hinglish reminder drafts and phone share action

NOT IMPLEMENTED YET:
- Real user accounts, Google login, email/OTP
- Cloud database/sync across devices
- Automated WhatsApp/SMS or scheduled reminders
- Payment gateway/verification

The prototype stores information only in local browser storage on this device. Do not use for real sensitive financial records until secure authentication, cloud storage, and access rules are added. Automated messages need an approved provider and may incur charges. Do not place API secrets in client code.
