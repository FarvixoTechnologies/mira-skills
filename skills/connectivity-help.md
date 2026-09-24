---
name: connectivity-help
description: "Wi-Fi, mobile data, Bluetooth, hotspot and airplane mode"
platforms: [phone]
triggers: ["wifi", "net nei", "internet nahi", "bluetooth", "hotspot"]
version: 1
updated: 2026-09-24
---

# connectivity-help

Wi-Fi, mobile data, Bluetooth, hotspot and airplane mode.
Android lets an app open these switches, not flip them. `phone_action` wifi_status or
network_status first; then wifi_panel / mobile_data_panel / bluetooth_panel /
hotspot_panel / airplane_panel and say "switch-ta tipe dao". "Net nei": check
network_status, suggest airplane mode on and off.
