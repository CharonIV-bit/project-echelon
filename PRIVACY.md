# Privacy overview

This document describes Project Echelon's current development direction. It will be expanded before a public release.

## Microsoft account authentication

Microsoft account sign-in takes place through Microsoft's authentication interface. Project Echelon never asks users to enter their Microsoft password into the launcher and does not receive or store that password.

Project Echelon requests only the authorization needed to connect the user's Microsoft/Xbox identity with Minecraft Services, verify Minecraft: Java Edition ownership, and retrieve the associated Minecraft profile.

## Local launcher profile

The launcher can protect its own local profile with a separate local password. That password is unrelated to the user's Microsoft account. Security-sensitive local data is protected using Windows account-bound storage.

## Data collection

Project Echelon does not currently operate remote analytics, advertising, tracking, or account databases. Prototype preferences and local launcher-profile data remain on the user's Windows device.

## Future changes

If a future feature requires an online service, this notice will be updated before that feature is released, including the data involved, its purpose, retention, and deletion options.

## Contact

Privacy or security questions can be submitted through this repository's Issues page.
