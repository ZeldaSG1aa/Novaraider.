# NovaRaider — Android WebView (GitHub-ready)

Lightweight Android project that opens `https://novaraider.net/en/game` in a WebView.

### Features
- Android Studio / GitHub friendly structure
- WebView main activity (Java)
- Placeholder app icon
- GitHub Actions workflow (actions/checkout@v4 + gradle/gradle-build-action@v2)
  that builds the APK and uploads it to the workflow artifacts.

To build on GitHub Actions, push this repository and the workflow will produce an APK artifact.
You may want to set up signing to produce a properly signed release APK.
