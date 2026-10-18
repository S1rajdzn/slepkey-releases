# Slepkey

A compact, offline keyboard-sound utility for Windows 10/11 x64.

**[Download Slepkey 1.0.0](https://github.com/S1rajdzn/slepkey-releases/releases/download/v1.0.0/slepkey-1.0.0-windows-x64.zip)**

[Release notes and checksums](https://github.com/S1rajdzn/slepkey-releases/releases/latest)

## Run the app

1. Download the ZIP and extract the complete archive into a stable folder.
2. Run `slepkey.exe`.
3. Choose a sound profile, adjust volume, or mute sounds. Settings contains playback-device selection and optional startup.

Closing the panel hides it to the tray. Choose Exit from the tray menu to quit.
Run `Add slepkey to Search.cmd` to add a Start Menu shortcut. After moving or renaming the app folder, rerun that helper and, if startup is enabled, switch startup off and on to update its path.

## Features and privacy

- Six sound profiles, adjustable volume, native playback-device selector, and tray controls.
- Native Win32 and WASAPI application with embedded sounds, fonts, and artwork.
- No application network client, telemetry, or stored typed-text history.
- Preferences remain in `%APPDATA%\slepkey\config.ini`.

## Release status

The current release is **unsigned**. Windows may show an unknown-publisher or SmartScreen warning.

The 2026-10-18 release passed 32 Rust tests and 21 packaged-runtime smoke checks. The dependency audit found no known vulnerabilities or warnings, and Microsoft Defender reported no threats in the final EXE and ZIP. These checks do not guarantee safety or compatibility on every system.

Testing used Windows build 26200 x64. Clean Windows 10/11 machine testing, extended soak testing, and physical audio-device reconnect testing remain outstanding.

## License and feedback

The app is distributed under the MIT license. Keep the included license and third-party notices with the app. The ZIP includes font licenses, the Mechvibes MIT notice, and sound-provenance details.

This repository hosts public downloads and issue reports. Report problems in [Issues](https://github.com/S1rajdzn/slepkey-releases/issues), including your Windows version, audio device, and steps to reproduce.
