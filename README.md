# NOTORYX PRO downloads

**One app for MeshCore and Meshtastic LoRa radios.** Part of the **NOTORYX** off-grid communications family. **No Towers. No Limits.**

This repository hosts builds of NOTORYX PRO for Android, iPhone and Mac. Get them from **[Releases](../../releases)**.

## Status: test 5 out

**[0.5.0 test 5](../../releases/tag/v0.5.0-test.5)** fixes the Meshtastic Bluetooth connection failure in test 4 and adds other-mesh traffic, MQTT feeds, channel bridging, Spanish, more radio settings and saved traces. Nothing new in this build has been tried on a real radio yet, so please report what works.

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

## Installs alongside other NOTORYX apps

| | App ID |
|---|---|
| Android | `com.bastionmesh.notoryx_pro` |
| iPhone / Mac | `com.bastionmesh.notoryxPro` |

## License

NOTORYX PRO is free software under the GNU General Public License v3.0. Source: [notoryx-PRO](https://github.com/TheLogsAreScreaming/notoryx-PRO).
