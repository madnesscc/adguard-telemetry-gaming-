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

Last Updated: February 2026
