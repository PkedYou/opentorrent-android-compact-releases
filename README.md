# OpenTorrent Compact

An optimized, separate Android fork of OpenTorrent 0.4.1. All original CPU architectures and app features are retained. Release builds remove debug tooling and unused dependency code/resources, and compress native libraries.

This app installs alongside the original OpenTorrent. It has its own app data and update channel; it does not replace the original or automatically import its settings/download queue. Existing original app data remains with the original app.

Future Compact updates appear inside Compact and use Android-confirmed in-place installation. The app verifies HTTPS, SHA-256, identity, increasing version code and its signing certificate. This repository contains APKs and public release metadata only; no private user data or signing keys.
