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

Dependecies:

```sh
$ flatpak install org.freedesktop.Sdk//22.08 org.electronjs.Electron2.BaseApp//22.08
```

Build and install:

```sh
$ flatpak-builder --user --install --force-clean build-dir com.pachca.Pachca.yml
```

