# alasr-cables-app

Android app (Kotlin) for Alasr Cables:
- PIN lock
- Add operation (name, diameter, turns) with auto date
- Points calculator per diameter (1, 1.5, 2, 3, 4, 6, 8, 9, 10, 16, 25, 35 mm)
- RecyclerView history + search by name/date + delete specific item
- Total points
- Export multi-page PDF + Share
- Modern Splash + AS crown icon
- Settings (change PIN)

## Build (Android Studio)
1. Open the project folder.
2. Let Gradle sync.
3. Run on device.

## Build (GitHub Actions)
1. Create a new GitHub repo (public or private).
2. Upload this folder's contents.
3. Go to **Actions** tab → run starts automatically.
4. Download APK from the workflow **Artifacts** named `Alasr.apk`.

Default PIN: `1234`
