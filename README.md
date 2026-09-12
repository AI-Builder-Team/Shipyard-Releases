# Shipyard releases

Official macOS installers and signed updates for Shipyard.

[Download the latest release](https://github.com/AI-Builder-Team/Shipyard-Releases/releases/latest)

The first release is being prepared. This repository contains distribution files only; the application source is maintained separately.

## Install

Choose the `.dmg` ending in `aarch64` for Apple Silicon or `x86_64` for Intel. Copy Shipyard to Applications. Once an updater-enabled version is installed, use **App updates** in the header to download future versions and install when ready to restart.

Initial releases are not Apple notarized. The `.app.tar.gz` and `.sig` files are used by the built-in updater; `latest.json` describes the current release. Update signatures verify publisher authenticity and are separate from Apple code signing.

Publishing compiled software here does not grant a source-code license.
