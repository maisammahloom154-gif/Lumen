# Lumen APK project

1. Put every file in this folder into a new GitHub repository (branch: main).
2. If the hidden .github folder did not upload, create the file
   .github/workflows/build-apk.yml on GitHub and paste in WORKFLOW-copy-me.yml.
3. Open the Actions tab, wait for "Build APK" to finish (about 5 minutes).
4. Open the finished run, download the Lumen-APK artifact, unzip it, install app-debug.apk.

To change the app, edit www/index.html and commit. GitHub rebuilds the APK.
