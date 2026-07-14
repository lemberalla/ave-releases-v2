# AVE Releases

Official macOS releases and signed Sparkle update feed for [AVE](https://aivideoeditor.app), the local-first AI video editor.

[![Latest release](https://img.shields.io/github/v/release/lemberalla/ave-releases-v2?display_name=tag&label=latest)](https://github.com/lemberalla/ave-releases-v2/releases/latest)
![macOS 14+](https://img.shields.io/badge/macOS-14%2B-111111?logo=apple)
![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-M1%20or%20later-111111?logo=apple)

[Download AVE](https://aivideoeditor.app/download/) · [Release notes](https://aivideoeditor.app/release-notes/) · [AVE website](https://aivideoeditor.app)

## Latest release

AVE 1.0.17 includes the complete Local AI engine, Local Vision Lite, and Fast Captions so local analysis works without a separate runtime installation.

The download is approximately **1.22 GB** because the starter AI engine and models are included in the app package.

## Install

1. Download the latest DMG from [GitHub Releases](https://github.com/lemberalla/ave-releases-v2/releases/latest).
2. Open the DMG and drag AVE into Applications.
3. Launch AVE and start a local project.

AVE currently requires macOS 14 or later on an Apple Silicon Mac.

## What this repository contains

- Signed and notarized AVE DMG installers.
- Signed ZIP packages used by the in-app Sparkle updater.
- The public Sparkle `appcast.xml` update feed.
- Release notes and checksums for published artifacts.

Existing AVE 1.0.15 and 1.0.16 installations first receive a small compatibility update, then AVE downloads and installs the complete package. Projects, settings, accounts, downloaded models, and linked model folders remain in place.

## Support

This repository is distribution-only, so GitHub Issues are disabled. Use **Send Feedback** inside AVE or email [support@tinythings.app](mailto:support@tinythings.app) for help.
