![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

![Pi-hole Generation](https://github.com/madnesscc/adguard-telemetry-gaming-/actions/workflows/generate_pihole_lists.yml/badge.svg)

## 📥 Download & Import

| Filter Typ | AdGuard / uBlock (Standard) | Pi-hole / DNS (Clean) |
| :--- | :--- | :--- |
| **Gaming Whitelist** | [Ansehen](./Gaming%20Publisher%20-%20Whitelist) | [Download (Raw)](./pihole-whitelist.txt) |
| **Telemetry Block** | [Ansehen](./block%20gaming%20telemetry) | [Download (Raw)](./pihole-telemetry.txt) |


🛡️ Gaming Telemetry Blocker (AdGuard Optimized)

This project provides high-performance filter lists specifically designed for AdGuard Home and AdGuard Apps.
🚀 Easy Setup

In AdGuard Home, both the Blacklist and the Whitelist are added in the same section. AdGuard automatically detects whether a rule blocks or allows a domain based on the syntax.
How to add the lists:

    Go to Filters -> DNS Blocklists.

    Click on Add Blocklist -> Add a custom list.

    Add the Blocklist:

        Name: Gaming Telemetry Block

        URL: Raw-Link

    Add the Allowlist (in the same menu!):

        Name: Gaming Services Allowlist

        URL: Raw-Link

💡 How it works (The Syntax)

You don't need to worry about adding them to different menus. The files use specific prefixes that AdGuard understands natively:

    ||domain.com^ (in your Blocklist): Tells AdGuard to block this domain and all its subdomains.

    @@||domain.com^ (in your Allowlist): Tells AdGuard to unblock/permit this domain. Exceptions (@@) always win over block rules, ensuring your games always have access to login and sync servers.

🎮 Covered Publishers

    Steam / Valve, Epic Games, Ubisoft

    EA (Electronic Arts), Activision / Blizzard

    Riot Games, Rockstar Games, 2K, Bethesda

    Xbox / Microsoft Gaming, Unity Engine

Maintainer: Custom List - Community

! Version: 1.0.0
! Author: madnesscc
! License: MIT
! Last modified: 2026-02-28
! --------------------------------------------------

---
**Disclaimer:** This project is not affiliated with Amazon, NVIDIA, Microsoft, Google, or any other cloud gaming provider. All product names, logos, and brands are property of their respective owners. This list is maintained by **madnesscc** for community use under the MIT License.
