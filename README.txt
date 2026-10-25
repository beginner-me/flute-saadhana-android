FLUTE SAADHANA — BUILD AN APK WITHOUT ANDROID STUDIO

This project wraps your supplied Flute Saadhana HTML page in an Android app and
declares Android microphone permission. A GitHub Actions workflow is included so
GitHub can compile the APK in the cloud.

STEPS:
1. Sign in to GitHub or create a free account at https://github.com
2. Create a new repository. A simple name is: flute-saadhana-android
3. Upload/extract all the files in this ZIP into the repository. Make sure the
   .github/workflows/build-apk.yml file is included.
4. Commit the files to the main branch.
5. Open the repository's Actions tab.
6. Choose "Build Flute Saadhana APK" and click "Run workflow" if it has not started.
7. Wait for the workflow to finish successfully.
8. Open the completed workflow run, scroll to Artifacts, and download
   "Flute-Saadhana-APK". Extract the downloaded artifact ZIP to get app-debug.apk.
9. Transfer app-debug.apk to your Samsung Galaxy A35 and tap it to install.
   If Android asks, allow installing unknown apps for the app you used to open it.
10. Launch Flute Saadhana and grant microphone permission when prompted.

NOTES:
- This is a debug APK intended for personal/testing use, not Play Store release.
- You do not need Android Studio on your computer; GitHub builds the APK online.
- The project embeds the HTML file supplied in the conversation.
- If the GitHub workflow fails, open its log and share the error so it can be fixed.
