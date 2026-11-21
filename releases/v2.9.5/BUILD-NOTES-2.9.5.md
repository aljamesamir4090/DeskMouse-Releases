# Desk Mouse 2.9.5 preview build files

- `DeskMouse-Setup-v2.9.5-x64.exe`: Windows x64 installer, built from desktop source commit `8c95f87`. Setup requests administrator access.
- `DeskMouse-Android-Debug-2.9.5.apk`: Android debug/testing build, version code 23. It uses the `.debug` application ID and Android debug signing key, so it cannot update the production Android app.

These are preview binaries. The publisher Android keystore and signed update-manifest key are not configured in this workspace, and the Windows installer is not Authenticode-signed. Existing production installations will not receive automatic updates from these files.
