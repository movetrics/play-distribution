# Movetrics Play

A simple home for movement on Windows 11 x64.

**Development Preview — first release preparation.** The [Releases page](https://github.com/movetrics/play-distribution/releases) contains published installers and portable downloads when available.

Movetrics Play includes Tidekeepers 0.3.0-dev.16 and offers Balance Canvas, Force Studio and Orbit through its library. Choose **Download**, then **Play**. **Try demo** uses synthetic input. No account is required; installed activities remain playable offline.

This repository contains the curated public catalog and approved binary packages. Game source, hardware research, production signing secrets and user recordings are not published here.

## Catalog authenticity

`catalog.json` is authenticated by the detached Ed25519 signature in `catalog.json.sig`. Play pins the publisher public key and checks each package's SHA-256, exact size and complete file inventory before activation. The public key fingerprint (SHA-256 of the PEM file) is `54772011fe56e39c07b0f945fe8cdc0964213dea89a13b13f227284db34d9333`.

Only explicitly selected releases enter this catalog. Version numbers do not automatically promote development packages. Release assets become immutable on publication.

## Preview status

Physical hardware acceptance beyond ten minutes and clean-machine acceptance are pending. Binaries are unsigned by Windows Authenticode; catalog signing is a separate authenticity check. Views show relative balance and original wire-unit measurements. Calibrated force/COP and desktop mouse control are unavailable in this preview.

Local saves and recordings remain on your computer and are preserved by ordinary uninstall. See each download's included notices for component licenses. Movetrics names and marks remain reserved; this repository does not grant a license to private source code.
