# FileMp3

### Your audio. Your library. On your device.

A native iPhone and iPad audio player by **Ave Studios**, designed for personal audio libraries, flexible playlists, and background listening.

**Swift | SwiftUI | AVFoundation | MediaPlayer | StoreKit 2 | iOS/iPadOS 17+**

[Support](https://filemp3-support.duskybuddy3.chatgpt.site/) | [Privacy](https://filemp3-support.duskybuddy3.chatgpt.site/privacy.html)

## Product experience

- Import personal audio through Files and organize it in an on-device library.
- Search, rename, share, and organize tracks into playlists.
- Sort A-Z, Z-A, by date added, or in a custom drag-to-reorder sequence.
- Finish custom ordering with Done to return to ordinary playlist interaction.
- Add tracks to the playback queue or play them next from the track menu.
- Customize songs and playlists with artwork, with a blank CD fallback.
- Expand the mini player into Now Playing with seek, shuffle, repeat, and queue controls.
- Keep Library and Playlists navigation accessible during playback.
- Listen in the background with lock-screen playback controls.
- Restore paid access through the Apple Account without a separate app login.

## Engineering highlights

| Area | Implementation |
| --- | --- |
| Interface | Native SwiftUI library, playlist, and player views |
| Playback | AVAudioPlayer and AVAudioSession playback configuration |
| System integration | MediaPlayer Now Playing and remote controls |
| Persistence | Atomic local library writes and periodic playback-position saving |
| Commerce | StoreKit 2 products, verified entitlements, and Restore Purchases |
| Privacy | On-device audio, artwork, playlists, and playback state; no app accounts, advertising, or analytics services |
| Accessibility | VoiceOver labels and native iPhone/iPad layouts |

## Plans

The free tier supports 500 successful imports per calendar month on each device. Unlimited local imports are offered through a $4.99 monthly subscription or a $99.99 lifetime purchase, subject to device storage. These are configured US prices; storefront prices may differ. Cloud audio storage is not included.

## Release status

Version 1.0, build 4 was submitted to Apple App Review on October 27, 2026. Submission does not imply approval or public App Store availability. Monthly purchase and Restore Purchases were reported as passing TestFlight sandbox testing.

## Resume summary

> Developed FileMp3, a native iPhone/iPad audio player using SwiftUI, AVFoundation, MediaPlayer, and StoreKit 2, featuring local library persistence, editable playlists, playback queues, background audio, artwork customization, and account-free in-app purchases. Prepared and submitted the app for Apple App Review.

## About this repository

This is a public portfolio showcase, not an open-source release of the app. Production source, signing files, private repository history, and personal audio are intentionally excluded.

**Ave Studios** | [avestudiosofficial@gmail.com](mailto:avestudiosofficial@gmail.com)

Copyright 2026 Ave Studios. All rights reserved.
