# React Native Template iOS Installer

GitHub Pages installer repository for the OneLane React Native/Expo template. `./.ol/ol.cmd template publish reactnative` in the parent repo builds the signed IPA, updates `ipa/reactnative-install.ipa`, regenerates `manifest.plist` and `release.json`, pushes this repo, and verifies the exact public release.

The OTA install is valid only for UDIDs included in the package's Ad Hoc provisioning profile.
