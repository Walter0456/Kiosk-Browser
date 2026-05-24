# OmniKiosk Browser

A secure Android kiosk browser built for tablets and dedicated display devices.

OmniKiosk Browser is designed for real-world commercial kiosk deployments where websites often block iframe embedding. Instead of relying on iframe rendering, the app uses a native Android WebView kiosk architecture for broader compatibility and more stable behavior.

## Screenshots

![Front Page](./Front%20Page.png)

![Front Page (Password Protected)](./Front%20Page%20but%20lock%20was%20added.png)

![Entering Lock Screen](./Entering%20Lock.png)

## Key Features

- Native kiosk browsing engine (Android WebView)
- Hidden admin unlock gesture
- Password-protected settings panel
- Persistent URL and kiosk preferences
- Kiosk reload controls for fast maintenance
- Built for touch-first tablet use

## Compatibility

| Platform | Status |
|---|---|
| Android tablets (modern Android) | Supported |
| Amazon Fire tablets (Fire OS) | Supported |
| iOS / iPadOS | Not currently supported |
| macOS / Windows desktop app | Not currently supported |

## Use Cases

- Retail self-service screens
- Internal company dashboard kiosks
- School / clinic information terminals
- Network-local web panel access

## APK Installation

1. Download the latest APK from Releases.
2. Transfer APK to your Android/Fire tablet.
3. Enable install from unknown sources (if required).
4. Install and launch the app.
5. Configure kiosk URL and admin password on first setup.

## Security Notes

- Set a strong admin password during first launch.
- Restrict access to device settings for kiosk deployments.
- Use device pinning / lock task mode for hardened installs.

## Project Scope

This public repository is intentionally documentation-focused and release-oriented.
Source code is maintained separately.

## License

All rights reserved unless otherwise specified by the repository owner.
