# Project Echelon

<p align="center">
  <img src="assets/project-echelon-logo.png" alt="Project Echelon logo" width="180">
</p>

**Minecraft, refined.**

Project Echelon is a Windows launcher and client for Minecraft: Java Edition. It is being built to bring account management, Minecraft versions, game settings, performance options, and Echelon modules together in one place.

## Project status

Project Echelon is currently in active development. The launcher interface, local profile protection, settings, account management, and Microsoft sign-in experience are being built first. Minecraft launching is not available yet.

## Planned experience

- A modern Windows launcher with Project Echelon's liquid-glass design
- Microsoft and Minecraft account connection through Microsoft's sign-in interface
- Support for multiple Minecraft accounts
- Minecraft version and profile selection
- Game, display, performance, memory, and Java runtime settings
- HUD and utility modules such as an FPS counter, coordinates, keystrokes, and zoom
- A curated Content Hub for installing shaders and resource packs with one click
- An in-game menu for configuring Project Echelon modules

## Content Hub

Project Echelon will include its own Content Hub where players can browse and install shaders or resource packs directly into their selected Minecraft profile. The launcher will handle the download and place the content in the correct folder, so players do not have to move files manually.

This will not be an open, community-run marketplace. Public uploads will not be accepted. Every listing will be selected, reviewed, packaged, and published by the Project Echelon team before it appears in the launcher. Listings will identify the original creator and source, and content will only be distributed when its license or the creator's permission allows it.

The hub will be limited to reviewed shader and resource-pack content. It will not distribute executable files, standalone installers, cheat modules, or unknown mod files. Listed content will receive a **Project Echelon Verified** label after review.

Read the planned [Content Hub policy](CONTENT_HUB.md).

## Microsoft and Minecraft authentication

Project Echelon uses Microsoft's official authentication flow. Microsoft handles the user's password, security keys, and account verification. Project Echelon never asks users to type their Microsoft password into the launcher and does not receive or store Microsoft passwords.

The intended sign-in chain is:

1. Microsoft account authentication
2. Xbox Live user authentication
3. XSTS authorization
4. Minecraft Services authentication
5. Minecraft: Java Edition ownership and profile verification

Project Echelon uses its own registered Microsoft Entra Application ID and does not impersonate another launcher or reuse another application's credentials.

## Fair play

Project Echelon is not a cheat client. It will not contain modules, shaders, resource packs, or other content designed to let users cheat or gain an unfair advantage.

Read the full [fair-play statement](FAIR_PLAY.md).

## Privacy and security

Account authentication is performed by Microsoft. Sensitive local account information is protected using Windows account-bound storage. Project Echelon does not operate an advertising or analytics platform and does not sell user information.

Read the current [privacy overview](PRIVACY.md).

## Availability

Project Echelon is not publicly released yet. This repository currently exists to document the project, its authentication design, and its fair-play scope while development continues.

## Contact

Questions about Project Echelon can be submitted through this repository's Issues page.

## Independence notice

Project Echelon is an independent project and is not affiliated with, endorsed by, or sponsored by Mojang Studios or Microsoft. Minecraft is a trademark of Microsoft Corporation.
