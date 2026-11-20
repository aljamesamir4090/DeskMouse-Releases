# Desk Mouse 2.9.4 build files

- `DeskMouseDesktop-2.9.4-x64.exe`: self-contained Windows x64 portable app.
- `DeskMouse-Android-Debug-2.9.4.apk`: debug/testing build, version code 22. It uses the `.debug` application ID and cannot update the production Android app.

Only these two assets belong to the 2.9.4 release. The Android production signing keystore and the signed stable update-manifest key are not available in this workspace, so these files do not update existing production installs automatically.
