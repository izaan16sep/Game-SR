Stationary Roulette - local Android app (APK builds itself on GitHub, free)
===========================================================================
The game files live INSIDE the app (www/), so it opens like a normal app, not in Chrome.
Bot and same-phone modes work offline. Online rooms still need internet.

1. Make a free GitHub account and create a new repository.
2. Upload every file in this folder, keeping the folders (.github/workflows/build-apk.yml must keep that path).
3. Open the repo's Actions tab > "Build APK" > Run workflow (it also runs on every upload).
4. After ~5 minutes open the finished run, scroll to Artifacts, download "Roulette-APK" (a zip), unzip, install app-debug.apk.
5. To update the game: replace www/index.html in the repo; the APK rebuilds.
