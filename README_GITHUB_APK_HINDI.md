# iLauncher APK build package (Hindi)

Is package mein Android source ZIP aur GitHub Actions workflow diya gaya hai. APK abhi bani hui nahi hai; GitHub Actions use build karega.

## Mobile se istemal
1. Is package ko extract karein.
2. GitHub repository ke root mein `iLauncher_iOS_Android_Source-1.zip` upload karein (source zip ka naam isi tarah rakhein).
3. Repository mein `.github/workflows/build-apk.yml` path par nayi file banayein aur is package ke `build-apk.yml` ka poora content paste karein. GitHub par: Add file > Create new file; filename mein `.github/workflows/build-apk.yml` likhein.
4. Commit changes karein.
5. Repository ke Actions tab mein `Build iLauncher APK` workflow kholein, zarurat ho to Run workflow dabayein.
6. Build successful hone par run ke neeche Artifacts mein `iLauncher-debug-apk` download karein. ZIP ko extract karke `app-debug.apk` install karein.

Note: Public repository par source public hoga. Build fail ho to Actions ke red error ka screenshot share karein.
