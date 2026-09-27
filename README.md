# Kontime for Android — releases

Signed Android builds of **Kontime**, the working-time record app for employees by Komma SoftHouse.

## Install

1. Open the [latest release](https://github.com/komma-softhouse/kontime-app-android-releases/releases/latest) on your phone.
2. Download `Kontime-<version>.apk`.
3. Open it. The first time, Android asks you to allow installing apps from your browser; allow it once and tap **Install**.

## Update

Kontime checks this repository itself: **More → Updates → Check for updates**, then **Download and install**. Every build is signed with the same key, so updates install over the current version and keep your data.

## Verify a download

Each release ships a `.sha256` file next to the APK:

```bash
shasum -a 256 -c Kontime-<version>.apk.sha256
```

## Pairing

Ask your employer for the pairing QR on your employee card, or use your employee code and PIN. Kontime only talks to your employer's own Kontime server.

## Support

support@kommasofthouse.com · https://kontime.kommasofthouse.com