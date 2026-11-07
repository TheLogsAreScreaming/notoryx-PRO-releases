# NOTORYX PRO downloads

**One app for MeshCore and Meshtastic LoRa radios.** Part of the **NOTORYX** off-grid communications family. **No Towers. No Limits.**

This repository hosts builds of NOTORYX PRO for Android, iPhone and Mac. Get them from **[Releases](../../releases)**.

## Status: first test build out

**[0.1.0 test 1](../../releases/tag/v0.1.0-test.1)** connects to MeshCore and Meshtastic radios over Bluetooth, Wi-Fi or USB (Android), shows one inbox for both meshes, sends and receives with delivery status and retries, reconnects by itself, and shows how each message travelled. It hasn't been tried on real radios yet, so please report what works.

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
| Map, diagnostics, verified senders | Planned |

## Installs alongside other NOTORYX apps

| | App ID |
|---|---|
| Android | `com.bastionmesh.notoryx_pro` |
| iPhone / Mac | `com.bastionmesh.notoryxPro` |

## License

NOTORYX PRO is free software under the GNU General Public License v3.0. Source: [notoryx-PRO](https://github.com/TheLogsAreScreaming/notoryx-PRO).
