# Desk Mouse 2.9.5

- `DeskMouse-Android-v2.9.5.apk`: Android release build, version code 23, signed with the new Desk Mouse release key.
- `DeskMouse-Setup-v2.9.5-x64.exe`: Windows x64 installer from the existing 2.9.5 build. This installer is not Authenticode-signed, so Windows may show a publisher warning.

## Android upgrade notice

The Android signing key changed for this build because the previous private key could not be recovered. Existing production installs signed with the old key (including 2.9.0–2.9.3) cannot update in place. Uninstall the old app before installing this APK; uninstalling may remove saved computers and app settings. Back up anything important first.

## SHA-256

- Android: 32fe3c8cde166bdec42366cafd6ccb04f8a3ad828199083a93daf81049fc183a
- Windows: 4eb7066dff7692dbb6da1ef287b6b7eb490c0b69ad1105c22f029a77ed02dfbe