<p align="center">
  <img width="128" src="macos-keystroke-counter/Assets.xcassets/icon_512x512@2x.png">
</p>

<h1 align="center">KeyCount</h1>

<p align="center">
  An open source macOS menu bar application that tracks and displays keystroke count and can (optionally) send real-time-like keystroke data to a specified http/https endpoint
</p>

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaHFsaDJyZHZ6dmtxMnI3MG1qc2M4bXZpOTBrZGl1c3ljMmhnaWYzOSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/WB1Y5VlmofpfQwjpZt/source.gif">
</p>

## Key features
1. Count daily keystrokes and display them in the macOS menu bar
2. Optionally save and view historic daily keystroke values
3. Optionally export keystroke data to an external http/https endpoint in configurable intervals

## To run the app:
1. Download the [latest release](https://github.com/MarcusDelvecchio/KeyCount/releases#latest)
2. Run the app and grant permissions (see below)

## Granting permissions
This application requires your permission to receive events from macOS in order to count and display your keystrokes in the menu bar.

On newer versions of macOS (10.15+) there is an Input Monitoring menu under Security & Privacy within the System Preferences app, and macos-keystroke-counter will appear there automatically the first time you run it. Simply unlock this menu and check the box next to macos-keystroke-counter to enable it.

## Want to contribute?
1. Code away
2. Create a PR
3. We'll merge the PR if all looks good!

_Given the nature of this keystroke counting application, security is paramount. We emphasize the importance of thorough code reviews to ensure the absence of any malicious content or security concerns. Our team is committed to performing rigorous reviews, and we also encourage contributors to uphold the same level of diligence in their code submissions._

## Note on Attribution
This project is open source under the MIT License. If you use or modify this code, kindly attribute it to [KeyCount](https://github.com/MarcusDelvecchio/KeyCount) and provide a link back to this repository.

## On Data Export Functionalities
Data export functionalities are currently in pre-release and are not available on the latest release. These features can be accessed on corresponding branches for [Firebase connection](https://github.com/MarcusDelvecchio/KeyCount/tree/environment/firebase) and [HTTP/HTTPS](https://github.com/MarcusDelvecchio/KeyCount/tree/environment/http) connection for data export.

The project can be cloned and installed from the corresponding branch and setup with the following steps:
1. Install Xcode from Mac App Store if not already installed
2. Open workspace file: macos-keystroke-counter.xcodeproj
3. Run
4. Grant permissions
5. Follow in-app HTTP/Firebase connection setup

### Other
Icon by Javier Aroche/ [via CC Liscence](https://creativecommons.org/licenses/by/4.0/)


