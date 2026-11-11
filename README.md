# Money Tracker — releases

Download the latest version from **[Releases](https://github.com/amalcpaulson/money-tracker-releases/releases/latest)**:
the file named `money-tracker-<version>.apk`.

## Installing

1. Download the APK on your Android phone (Android 8.0 or newer).
2. Open it. Android asks once to allow installs from your browser or file manager — allow it.
3. Tap **Install**.

## Updates

The app checks this page daily and tells you when a new version is out. Install it from
**Settings → Check for updates**. Your data stays on your phone through every update, and if
you are signed in with Google it is also synced to your own Google Drive first.

Before installing, the app verifies that the download matches the published SHA-256 checksum
and is signed by the same key as the version you have. Anything else is refused.

To check a download by hand:

```
shasum -a 256 money-tracker-<version>.apk
```

and compare with `money-tracker-<version>.apk.sha256` on the release.

## Privacy

[Privacy policy](https://amalcpaulson.github.io/money-tracker-releases/privacy.html)

## Problems

[Open an issue](https://github.com/amalcpaulson/money-tracker-releases/issues).
