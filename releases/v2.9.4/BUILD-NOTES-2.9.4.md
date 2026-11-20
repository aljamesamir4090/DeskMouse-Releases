# Desk Mouse 2.9.4 build files

- `DeskMouse-Setup-v2.9.4-x64.exe`: Windows x64 installer. Setup requests administrator access.
- `DeskMouse-Android-Debug-2.9.4.apk`: debug/testing build, version code 22. It uses the `.debug` application ID and cannot update the production Android app.

Only these two binaries belong to the 2.9.4 release. The Android production signing keystore and signed Windows update-manifest key are not available in this workspace, so existing production installs will not update automatically from this preview.
