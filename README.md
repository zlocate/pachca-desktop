# Pachca (Flatpak)

## ATTENTION: Untested software

This is a draft version of flatpak manifest for Pachca.

### Tests

All tests performed on Fedora 37 KDE Plasma.

- [x] Launching
- [x] Logging in
- [x] Messaging
- [x] Notifications
    - Choppy sound
- [x] Video call
    - Opens in a browser
- [x] System theme
    - Needs application restart for change

### TODO

- More tests
- System tray icon

### Build

```sh
$ flatpak-builder --user --install --force-clean build-dir com.pachca.Pachca.yml
```

