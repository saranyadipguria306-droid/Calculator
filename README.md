# Calculator — GitHub APK Builder

This project packages the supplied offline `index.html` Calculator inside an Android WebView.

## GitHub steps

1. Upload all files/folders in this project to your GitHub repository.
2. Commit them to the `main` branch.
3. Open the repository's **Actions** tab.
4. Select **Build Calculator APK**.
5. Tap **Run workflow**.
6. After it finishes, open the workflow run and download the artifact named **Calculator-debug-apk**.
7. Extract the artifact ZIP to get `app-debug.apk`.

The APK contains the HTML locally and does not request the Android INTERNET permission.
