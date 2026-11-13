# NOTORYX PRO downloads

**One app for MeshCore and Meshtastic LoRa radios.** Part of the **NOTORYX** off-grid communications family. **No Towers. No Limits.**

This repository hosts builds of NOTORYX PRO for Android, iPhone and Mac. Get them from **[Releases](../../releases)**.

## Status: test 11 out

**[0.11.0 test 11](../../releases/tag/v0.11.0-test.11)** adds a demo mode that needs no radio, an About screen with licences, French and German, and Windows notifications and USB radios. Nothing new has been tried on real hardware yet, so please report what works.

**[0.3.0 test 3](../../releases/tag/v0.3.0-test.3)** adds radio settings for both meshes (with area presets), repeater and room server admin, Meshtastic remote admin and telemetry history, unread counts, mute and notifications to everything in [test 2](../../releases/tag/v0.2.0-test.2). It hasn't been tried on real radios yet, so please report what works.

| Part | State |
|---|---|
| Project setup and CI | Done |
| Android, iPhone and Mac projects, permissions, blue app icon | Done |
| Bluetooth, USB (Android) and Wi-Fi links | Done |
| Automatic reconnect on Bluetooth, USB and Wi-Fi | Done |
| MeshCore protocol | Done |
| Meshtastic protocol | Done |
| One shared model for both meshes (radios, nodes, channels, messages) | Done |
| On-device database (messages keep how they arrived) | Done |
| Unified inbox, nodes, conversation and radio screens | Done |
| Messaging with delivery ticks, retries and reconnect | Done (test 1) |
| Map for both meshes with signal bars, routes and offline tiles | Done (test 2) |
| Diagnostics: packet log, radio readings, trace route, line of sight, delivery hints | Done (test 2) |
| Verified senders: QR codes, fingerprints, badges, name-clash warnings | Done (test 2) |
| MeshCore radio settings, repeater and room server admin | Done (test 3) |
| Meshtastic radio settings, remote admin and telemetry history | Done (test 3) |
| Notifications, unread counts, mute and area presets | Done (test 3) |
| Several radios at once, contacts beyond the radio's limit, channel management | Done (test 4) |
| Background connection, search, delete, export | Done (test 4) |
| MECP emergency messages | Done (test 4) |
| Other-mesh traffic, MQTT feeds, channel bridging, Spanish | Done (test 5) |
| Themes, restore, MAYDAY through mute, field reports, distress beacon, forwarding, scheduled messages, airtime savers | Done (test 6) |
| App lock, GPX and geofences, link planner, team setup, auto-replies | Done (test 7) |
| Optional encryption for saved messages | Done (test 8) |
| Windows build (untested) | Done (test 10) |
| Demo mode, About and licences, French and German, Windows notifications and USB | Done (test 11) |

## Installs alongside other NOTORYX apps

| | App ID |
|---|---|
| Android | `com.bastionmesh.notoryx_pro` |
| iPhone / Mac | `com.bastionmesh.notoryxPro` |

## License

NOTORYX PRO is free software under the GNU General Public License v3.0. Source: [notoryx-PRO](https://github.com/TheLogsAreScreaming/notoryx-PRO).
