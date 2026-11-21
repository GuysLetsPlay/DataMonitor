# Android Data Usage Tracker

[![Build APK](https://github.com/GuysLetsPlay/DataMonitor/actions/workflows/build-apk.yml/badge.svg)](https://github.com/GuysLetsPlay/DataMonitor/actions/workflows/build-apk.yml) [![Latest release](https://img.shields.io/github/v/release/GuysLetsPlay/DataMonitor?display_name=tag)](https://github.com/GuysLetsPlay/DataMonitor/releases/latest) [![License: GPLv3](https://img.shields.io/badge/License-GPLv3-blue.svg)](LICENSE)

Open-source Android data usage tracker for mobile and Wi-Fi. This GPLv3 fork of [Data Monitor](https://github.com/itsdrnoob/DataMonitor) adds home-screen date and network controls, SIM selection, and CSV export.

**Download:** [Get the latest APK](https://github.com/GuysLetsPlay/DataMonitor/releases/latest/download/app-debug.apk) · [Browse all releases](https://github.com/GuysLetsPlay/DataMonitor/releases)

## Features

- View total usage for the **last 7 days**, **last 14 days**, **month to date**, or a **custom date range**.
- See the exact start and end dates used by the total. Tap the date selector to choose a range.
- Choose **mobile + Wi-Fi**, **mobile only**, or **Wi-Fi only**.
- Choose **all SIMs** or an active SIM when Android exposes per-SIM statistics.
- Export the app usage breakdown to **CSV**.
- Also includes Data Monitor's weekly chart, per-app usage, billing-cycle tracking, alerts, and widgets.

## Install on Android

1. Download `app-debug.apk` from the [latest release](https://github.com/GuysLetsPlay/DataMonitor/releases/latest).
2. Open the downloaded file. Allow installs from your browser or file manager if Android asks.
3. Open Data Monitor and grant **Usage access**. Android requires this special access to read network usage statistics.
4. Use the home tab to select a period, date range, network scope, and SIM.

This fork's APK is debug-signed by GitHub Actions. Android may not install it as an update over a copy signed differently. If Android reports a signature conflict, uninstall the existing copy first; uninstalling can remove its local settings and history.

## SIM usage limitation

Android 10 and newer can restrict per-SIM network statistics to system or carrier apps. On affected devices, a selected SIM may fall back to the all-SIM total. The app explains this limitation. All-SIM mobile totals use Android's device-level counters.

## Privacy

Usage totals are read on the device through Android's Usage Stats APIs and do not require an account or a remote data service. Data Monitor also includes optional online features such as network diagnostics; see the [source code](https://github.com/GuysLetsPlay/DataMonitor) and Android permissions for details.

## Source and license

This project is based on [Data Monitor by Dr.NooB](https://github.com/itsdrnoob/DataMonitor) and licensed under the [GNU GPLv3](LICENSE). This fork adds home-screen period and SIM controls, explicit date selection, CSV export, and automated APK releases.

- [Browse source code](https://github.com/GuysLetsPlay/DataMonitor/tree/release/2.4.0)
- [Download the APK](https://github.com/GuysLetsPlay/DataMonitor/releases/latest)
- [Report a bug](https://github.com/GuysLetsPlay/DataMonitor/issues)
- [View APK build history](https://github.com/GuysLetsPlay/DataMonitor/actions/workflows/build-apk.yml)

Search terms: Android data usage tracker, Android mobile data monitor, SIM data usage, weekly data usage, monthly data usage, custom date range, Wi-Fi usage, CSV export.
