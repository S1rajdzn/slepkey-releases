# Slepkey

A compact, offline keyboard-sound utility for Windows 10/11 x64.

**[Download for Windows](https://github.com/S1rajdzn/slepkey-releases/releases/download/v1.0.0/SlepkeySetup.exe)**

## Run the app

1. Download `SlepkeySetup.exe`.
2. Run the installer and click Install.
3. Launch Slepkey, choose a sound profile, and adjust volume. Settings contains playback-device selection and optional startup.

Closing the panel hides it to the tray. Choose Exit from the tray menu to quit.
Setup installs to `%LOCALAPPDATA%\Programs\Slepkey`, creates a Start Menu shortcut, and adds Slepkey to Windows Installed apps for uninstalling. No manual extraction or administrator access is required. Startup remains opt-in; upgrades preserve your preferences and startup choice.

## Features and privacy

- Six sound profiles, adjustable volume, native playback-device selector, and tray controls.
- Native Win32 and WASAPI application with embedded sounds, fonts, and artwork.
- No application network client, telemetry, or stored typed-text history.
- Preferences remain in `%APPDATA%\slepkey\config.ini`.

## Release status

The app and installer are **unsigned**. Windows may show an unknown-publisher or SmartScreen warning.

The 2026-10-18 release passed 32 Rust tests, 21 installed-app runtime smoke checks and 30 installer lifecycle checks. The dependency audit found no known vulnerabilities or warnings, and Microsoft Defender reported no threats in the app, ZIP and installer. These checks do not guarantee safety or compatibility on every system.

Testing used Windows build 26200 x64. Clean Windows 10/11 machine testing, extended soak testing, and physical audio-device reconnect testing remain outstanding.

## License and feedback

The app is distributed under the MIT license. Keep the included license and third-party notices with the app. Setup installs the font licenses, Mechvibes MIT notice, and sound-provenance details alongside the app.

This repository hosts public downloads and issue reports. Report problems in [Issues](https://github.com/S1rajdzn/slepkey-releases/issues), including your Windows version, audio device, and steps to reproduce.
