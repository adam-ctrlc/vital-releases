# VITAL for Android

VITAL is a transformer alert management system: live voltage, current, load and temperature
readings, alerts the moment a threshold is crossed, relay control, and a full history of every
reading.

This repository hosts the **Android app downloads and updates**. VITAL also runs in any browser at
[vitalcoc.vercel.app](https://vitalcoc.vercel.app).

## Download

| | |
|---|---|
| **Newest release page** | [Latest release](https://github.com/adam-ctrlc/vital-releases/releases/latest) |
| **All releases** | [Releases](https://github.com/adam-ctrlc/vital-releases/releases) |
| **Requirements** | Android 7.0 or newer |

Not every release contains an APK: small updates are delivered inside the app (see
[Updates](#updates)). To install VITAL for the first time, use the newest release that lists a
`vital-vX.Y.Z.apk` file under **Assets**.

## Install

1. On your Android phone, open the newest release that has an APK and tap the `vital-vX.Y.Z.apk` file.
2. When the download finishes, tap the file to open it.
3. The first time, Android asks to allow installs from your browser. Tap **Settings**, switch on
   **Allow from this source**, then go back and tap **Install**.
4. Open VITAL and sign in, or create an account and wait for an admin to approve it.

Already have VITAL? Install the new APK over it the same way; your account and settings stay.

## Updates

VITAL checks for a new version every time you open it. Updates are required: when one is out, an
**Update required** screen lists what's new.

- **Most updates download inside the app.** Tap **Update now**, wait a few seconds, and VITAL
  restarts on the new version. Only the changed files are downloaded, with no reinstall.
- **Occasionally a new app version (APK) is needed**, when Android-level parts of the app change.
  The update screen then offers a **Download** button for the new APK; install it over the old one.

If a new version ever fails to start, VITAL goes back to the last version that worked by itself.

## What's in a release

- `latest.json`: what the app reads to find updates (version, release notes, file list).
- `f-<hash>` files: the app's files, each named by its content hash, so phones only download
  what changed.
- `vital-vX.Y.Z.apk`: the Android app, on releases that need one.

## License

Apache License 2.0. See [LICENSE](LICENSE).
