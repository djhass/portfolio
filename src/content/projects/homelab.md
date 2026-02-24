---
title: Microform HomeLab
description: A Dell Optiplex Used as a personal server for Home Assistant, Jellyfin, and more.
pubDate: 2026-02-02
heroImage: ../../assets/homelab.JPG
updatedDate: 2026-02-24
---

After replacing an optiplex machine at my intership at [Collaborate Technologies](https://collaboratetechnologies.com/#), I converted the old machine into a new homelab to replace my Raspberry Pi 3B+ running Home Assistant. It now hosts a .arr Jellyfin stack for watching movies and TV shows, HomeAssistant for controlling various IOT devices and automating my routine, Minecraft servers for both the Java and Bedrock versions, and piHole for managing unwanted network traffic. The challenges mostly involved learning to use Docker Compose to ensure stacks of containers work with each other smoothly. This server unites other projects in the home through Home Assistant. Many devices in the house can be controlled through the app as well as request movies to be added to Jellyfin. It even allows me to reboot the server from a Home Assistant interface.

- Hardware: Dell Optiplex 3040 + 2TB WD external drive
- OS: Debian GNU/Linux 13 (trixie)
- Orchestration: Docker Compose

Active Containers
* jellyseerr
* nzbget
* qbittorrent
* prowlarr
* radarr
* sonarr
* gluetun
* deunhealth
* jellyfin
* bazarr
* minecraft-java
* minecraft-bedrock
* pihole
