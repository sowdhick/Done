# Study Planner (Android)

A WebView wrapper around the Study Planner web app (app/src/main/assets/index.html).
Your plans are stored on the device and the app needs no internet permission.

## Build the APK without installing anything (GitHub)
1. Create a new GitHub repository and upload ALL files from this folder,
   including the hidden .github folder, keeping the folder structure.
2. Open the repo's Actions tab, choose "Build APK", tap Run workflow.
3. When it finishes, open the run and download the "study-planner-apk" artifact (a zip).
   Unzip it to get app-debug.apk, then install it on your phone
   (allow "Install unknown apps" for your browser or file manager).

## Build with Android Studio
Open this folder in Android Studio, let Gradle sync, then Build > Build APK(s).
The APK is in app/build/outputs/apk/debug/.

Note: this is a debug-signed APK, fine for personal use. For the Play Store you need a release build signed with your own key.
