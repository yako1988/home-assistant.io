---
title: Minecraft Server
description: Instructions on how to integrate a Minecraft server into Home Assistant.
logo: minecraft.png
ha_release: 0.106
ha_category: 
  - Binary Sensor
  - Sensor
ha_iot_class: Local Polling
ha_quality_scale: silver
ha_config_flow: true
ha_codeowners:
  - '@elmurato'
---

Minecraft servers allow players to play the sandbox video game [Minecraft](https://www.minecraft.net) by [Mojang AB](https://www.mojang.com) online or via a local area network with other players. The `Minecraft Server` integration lets you retreive information from a Minecraft server (Java edition) within Home Assistant.

<div class='note'>
The server must be version 1.7 or higher, since older versions don't expose any information.
</div>

## Configuration via the frontend

In the settings go to `Integrations`, click on the `+` sign to add an integration and click on **Minecraft Server**.
After completing the configuration flow, the Minecraft Server integration will be available.

## Binary sensors

This integration provides a binary sensor for the following information from a Minecraft server:

- Connection status

## Sensors

This integration provides sensors for the following information from a Minecraft server:

- Latency time
- Version
- Protocol version
- Number of online players (player names are available in state attributes)
- Number of maximum players
