DRUG SHOP MANAGER — ANDROID APP PROJECT

This is an Android WebView wrapper around the offline-first Drug Shop Manager app. It is an Android Studio/Gradle project, not a precompiled APK.

FEATURES IN THE APP
- UGX currency
- Medicine stock, batch and expiry tracking
- Low-stock and expiry alerts
- Sales, receipts and sales history
- Expense tracking and profit reports
- Prescription record log
- CSV export and JSON backup/restore
- Works offline; data is stored locally on this device

BUILD AN APK USING GITHUB (PHONE-FRIENDLY ROUTE)
1. Extract this ZIP into a folder named DrugShopManagerAndroidProject.
2. In your phone browser, sign in to GitHub and create a NEW private repository.
3. Upload the contents of this folder to the repository (keep the .github/workflows/build-apk.yml file and its folders).
4. Open the repository's Actions tab and select “Build Android APK”. If it has not run automatically, tap “Run workflow”.
5. Wait for the workflow to finish successfully.
6. Open the completed workflow run, scroll to Artifacts, and download “DrugShopManager-debug-apk”.
7. Extract the downloaded artifact ZIP to find app-debug.apk. Tap it to install. Android may ask you to allow installs from that browser or file manager.

BUILD WITH ANDROID STUDIO
Open this folder as a project, let Gradle sync, then choose Build > Build Bundle(s) / APK(s) > Build APK(s). The APK will be under app/build/outputs/apk/debug/.

IMPORTANT
- This environment did not have Android SDK/Gradle build tools available, so no compiled APK is included here. The GitHub Actions workflow is provided to build one.
- This is a starter app, not a validated pharmacy/dispensing system. Check local laws and professional requirements.
- Records are kept locally on the phone; there is no cloud sync, user login, or encryption. Back up regularly and protect prescription information.
- Before real use, test saving, closing/reopening, receipt printing/export and backup/restore on your phone.
