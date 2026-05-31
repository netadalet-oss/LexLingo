# DutchMb Android APK Projesi

Bu paket gerçek Android Gradle proje yapısıdır.

Repo kökünde şunlar görünmelidir:

- `.github`
- `app`
- `build.gradle`
- `settings.gradle`
- `README.md`

Önemli: `AndroidManifest.xml`, `MainActivity.java`, `styles.xml` kökte kalmamalıdır; bunlar `app/src/main/...` içindedir.

## APK üretme

GitHub'da:

1. Actions
2. Android APK üret
3. Run workflow
4. İş bitince Artifacts
5. DutchMb-APK indir
6. ZIP içinden `app-debug.apk` dosyasını çıkar
7. Telefonda kur