# Published component licences

Build commit: 5d63cf7b2b70f3ad0c85567e7e8447d69a25d47f

## dev.streamybox.launcher.debug

GPL-3.0, Apache-2.0, OFL-1.1

launcher/LICENSE and README: Arc/FLauncher provenance; Kotlin stdlib Apache-2.0; Inter font OFL-1.1; no native dependencies

[Corresponding source for APK 10032](release/dev.streamybox.launcher.debug-5d63cf7b2b70f3ad0c85567e7e8447d69a25d47f.tar.gz)

[Corresponding source for APK 10025](release/dev.streamybox.launcher.debug-5109ed32ed39c47319ef02cf510e4fab886c9cdb.tar.gz)

## dev.streamybox.settings

Streamybox-owned (all rights reserved), third-party: Apache-2.0

releaseRuntimeClasspath: Kotlin stdlib and ZXing; design/screensaver/contracts project code; no vendored native code or GPL/LGPL/AGPL dependencies

## dev.streamybox.keyboard

Streamybox-owned (all rights reserved), third-party: Apache-2.0

releaseRuntimeClasspath: Kotlin stdlib and project design/contracts; no native or GPL/LGPL/AGPL dependencies

## dev.streamybox.profiles

Streamybox-owned (all rights reserved), third-party: Apache-2.0

releaseRuntimeClasspath: Kotlin stdlib and project core/contracts/design; no native or GPL/LGPL/AGPL dependencies

## dev.streamybox.remote

Streamybox-owned (all rights reserved), third-party: Apache-2.0

releaseRuntimeClasspath: Kotlin stdlib, JmDNS 3.6.2, ZXing 3.5.3 and project design/contracts; no native or GPL/LGPL/AGPL dependencies

## dev.streamybox.store

Streamybox-owned (all rights reserved), third-party: Apache-2.0, MIT

releaseRuntimeClasspath: F-Droid index/download libraries (Apache, not client GPL), apksig, Kotlin serialization/coroutines/stdlib, Ktor, OkHttp/Okio Apache; kotlin-logging Apache; SLF4J MIT; no vendored native or GPL/LGPL/AGPL dependencies

## dev.streamybox.diag

Streamybox-owned (all rights reserved), third-party: Apache-2.0

releaseRuntimeClasspath: AndroidX Media3/collection/annotation, Kotlin and Guava/listenablefuture Apache; no vendored native or GPL/LGPL/AGPL dependencies

## dev.streamybox.player

GPL-3.0-or-later, GPL-2.0-or-later, LGPL-2.1-or-later, Apache-2.0, MIT, ISC, BSD-2-Clause, FTL, Zlib, curl

device/rock4d/player/NOTICE.md and native-sources.json: mpv ad5877e (GPL-2.0+), FFmpeg 16efe69 --enable-gpl --enable-version3 (GPL-3.0+), libplacebo 275f7de (LGPL-2.1+) with 4 submodules, libass/dav1d/FreeType, 8 sha256-pinned release tarballs, 5 patches (incl. spdif muxer and IEC 61937 HBR), NDK r27.1; scripts/lib/source-archive.py ships them in third_party/ and rebuilds the APK byte-identical (dex, resources, every lib/*.so from the pinned libmpv AAR)

[Corresponding source for APK 10032](release/dev.streamybox.player-5d63cf7b2b70f3ad0c85567e7e8447d69a25d47f.tar.gz)

## Streamybox OS 1.6.0

GPL/LGPL parts (AirPlay, FFmpeg, launcher, kernel modules, device tree) and upstream sources: [streamybox-os-1.6.0-source.tar.gz](https://github.com/tildoescode/streamybox-updates/releases/download/os-1.6.0/streamybox-os-1.6.0-source.tar.gz) (SHA-256 0b53859d6b40c3e3beef5e5213c6e0909c01b8940f44dd839999d4e9a3fad59f)

Streamybox original code: copyright Streamybox contributors, all rights reserved (no open-source licence granted). Third-party notices and licence texts are in licences/.

Withheld: dev.streamybox.airplay. Installed copies are retained.
