<div align="center">
  <img src="docs/steamlord-logo.png" alt="SteamLord" width="112">

  # SteamLord

  **A complete Steam companion for supported games, DLC, updates, fixes, customization, and recovery.**

  [![Latest Release](https://img.shields.io/github/v/release/LOoOrds/SteamLord?display_name=tag&sort=semver&style=for-the-badge&label=Latest&color=1688f8)](https://github.com/LOoOrds/SteamLord/releases/latest)
  [![Downloads](https://img.shields.io/github/downloads/LOoOrds/SteamLord/total?style=for-the-badge&label=Downloads&color=0ea5e9)](https://github.com/LOoOrds/SteamLord/releases)
  ![Platform](https://img.shields.io/badge/Windows-10%20%7C%2011-1688f8?style=for-the-badge&logo=windows11&logoColor=white)
  ![Architecture](https://img.shields.io/badge/Architecture-x64-075ea8?style=for-the-badge)

  [Download SteamLord](https://github.com/LOoOrds/SteamLord/releases/latest) | [Release History](https://github.com/LOoOrds/SteamLord/releases) | [Discord Support](https://discord.gg/bNhTGrEUum)
</div>

---

## What Is SteamLord?

SteamLord brings game management, updates, Online Fix, Bypass, and maintenance into one consistent experience inside the Steam client. Its controls appear where they are useful, including supported Steam Store pages and the Library, so daily operations do not require a separate game manager.

The project combines a Steam-integrated interface with native runtime components, a reliable download helper, automatic recovery, and a verified compatibility layer. The Setup is only the installer and maintenance companion for this wider system.

## Feature Overview

<table>
  <tr>
    <td align="center" width="33%"><img src="docs/icons/games.png" alt="Games and DLC" width="54"><br><strong>Games and DLC</strong><br><sub>Manage supported titles and their content.</sub></td>
    <td align="center" width="33%"><img src="docs/icons/online-fix.png" alt="Online Fix" width="54"><br><strong>Online Fix</strong><br><sub>Apply and manage supported fixes.</sub></td>
    <td align="center" width="33%"><img src="docs/icons/bypass.png" alt="Bypass" width="54"><br><strong>Bypass</strong><br><sub>Install available packages safely.</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="docs/icons/updates.png" alt="Game Updates" width="54"><br><strong>Game Updates</strong><br><sub>Keep managed titles current.</sub></td>
    <td align="center"><img src="docs/icons/achievements.png" alt="Achievements" width="54"><br><strong>Achievements</strong><br><sub>Supported achievement integration.</sub></td>
    <td align="center"><img src="docs/icons/steam-features.png" alt="Steam Features" width="54"><br><strong>Steam Features</strong><br><sub>Extended Steam compatibility.</sub></td>
  </tr>
  <tr>
    <td align="center"><img src="docs/icons/cloud-saves.png" alt="Cloud Saves" width="54"><br><strong>Cloud Saves</strong><br><sub>Optional save routing for supported games.</sub></td>
    <td align="center"><img src="docs/icons/requests.png" alt="Game Requests" width="54"><br><strong>Game Requests</strong><br><sub>Request titles and receive availability alerts.</sub></td>
    <td align="center"><img src="docs/icons/themes.png" alt="Steam Themes" width="54"><br><strong>Steam Themes</strong><br><sub>A modern Steam look in multiple colors.</sub></td>
  </tr>
</table>

## Features

### <img src="docs/icons/games.png" alt="" width="32" align="center"> Games and DLC

Add or remove supported titles directly from their Steam pages. SteamLord prepares the available DLC content and automates the required metadata, manifests, depot keys, and access information behind one clear action.

### <img src="docs/icons/online-fix.png" alt="" width="32" align="center"> Online Fix

Discover, apply, update, or remove supported Online Fix packages without leaving Steam. The same guided interface reports progress and the final result throughout the operation.

### <img src="docs/icons/bypass.png" alt="" width="32" align="center"> Bypass

Install or remove available Bypass packages through a controlled workflow. SteamLord checks availability and handles package preparation while keeping the action consistent with the rest of the interface.

### <img src="docs/icons/updates.png" alt="" width="32" align="center"> Game Updates

Scan installed SteamLord games for newer releases, review the available changes, and update one title or several together through one consistent workflow.

### <img src="docs/icons/achievements.png" alt="" width="32" align="center"> Achievements

Enable supported Steam achievement workflows for games managed through SteamLord while keeping the experience connected to the Steam client.

### <img src="docs/icons/steam-features.png" alt="" width="32" align="center"> Steam Features

SteamLord provides extended compatibility for supported Family Sharing, Remote Play, SteamStub, and Denuvo scenarios, with the required handling integrated into the native runtime.

### <img src="docs/icons/cloud-saves.png" alt="" width="32" align="center"> Cloud Saves

Optionally route cloud-save data for supported added games through the SteamLord Cloud Redirect runtime, keeping supported saves available through a managed SteamLord workflow.

### <img src="docs/icons/requests.png" alt="" width="32" align="center"> Game Requests

When a title is not available, SteamLord can record a request instead of leaving the user with a dead end. A notification appears when a previously requested game becomes available.

### <img src="docs/icons/themes.png" alt="" width="32" align="center"> Steam Themes

Give Steam a cleaner, modern appearance with SteamLord's glass-inspired interface and multiple color themes. The optional native styling extends the look across Steam itself, and users can disable it at any time to return to the original Steam appearance.

## Designed Around Steam

- Contextual controls appear on supported Steam game pages instead of living in a disconnected application.
- Active operations can be minimized to the SteamLord task dock and restored without losing their current state.
- Clear status, progress, and result dialogs keep Add, Update, Online Fix, and Bypass workflows consistent.
- Profile information shows license permissions and current usage limits without exposing private session data.
- Optional Adhkar reminders and interface preferences can be enabled or disabled independently.

## Reliable Operations

SteamLord is designed to recover cleanly when a connection or process is interrupted:

- Single and split downloads resume from verified progress instead of restarting completed work.
- Pending operations preserve enough state to continue safely after Steam or Windows restarts.
- Package metadata, file sizes, and cryptographic hashes are checked before files are applied.
- Installation steps use staging and controlled replacement to avoid leaving partially applied content behind.
- Missing or changed SteamLord runtime files can be detected and prepared for repair automatically.

## Updates and Compatibility

SteamLord keeps each layer current without handing compatibility decisions to an uncontrolled updater:

- Supported game updates are discovered from the SteamLord game index.
- Plugin and native component updates are verified and staged for the next Steam restart.
- The Millennium runtime is pinned to a SteamLord-verified version for stable compatibility.
- Requested games are checked efficiently and surfaced when they become available.
- Recovery rules can restore required files, replace changed versions, and remove retired components.

## Download

Download **`SteamLord Setup.exe`** from the [latest stable release](https://github.com/LOoOrds/SteamLord/releases/latest).

> Only download SteamLord from this repository or the official SteamLord Discord. Files re-uploaded by third parties are not supported.

## Requirements

- Windows 10 or Windows 11, 64-bit.
- Steam desktop client.
- Internet connection for installation, activation, downloads, and online content.
- Administrator permission during installation, repair, or removal.
- Microsoft Edge WebView2 Runtime. Windows 11 normally includes it; Setup offers the official Microsoft download when it is missing.

The official standalone Setup contains its required .NET runtime. A separate .NET installation is not required.

## Getting Started

1. Download `SteamLord Setup.exe` from the latest release.
2. Close Steam completely.
3. Run Setup and confirm the detected Steam installation.
4. Select **Install** and wait for verification to complete.
5. Start Steam, open SteamLord, and activate your license when requested.
6. Visit a supported game page to access the available SteamLord actions.

## Setup and Maintenance

The same Setup application supports the full installation lifecycle:

- **Install** deploys the verified SteamLord components and compatible Millennium runtime.
- **Update** installs a newer official SteamLord Setup when one is published.
- **Repair** restores missing or changed required files while preserving supported user data.
- **Uninstall** removes SteamLord and its managed components using the selected cleanup options.

SteamLord may also prepare verified updates or repairs while Steam is running. When a restart notice appears, close and reopen Steam to apply the pending operation.

## Release Integrity

Every official release includes a SHA-256 value in its GitHub Release notes. Verify the downloaded Setup with PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 ".\SteamLord Setup.exe"
```

The result must match the SHA-256 published with that exact release. Do not run the file when the values differ.

## Support

For activation, installation, game availability, or operation assistance, join the [official SteamLord Discord](https://discord.gg/bNhTGrEUum).

When reporting a problem, include the SteamLord version, Windows version, the affected AppID, and the exact message shown. Do not publish license keys, session files, tokens, or other private account data.

## Responsible Use

SteamLord is provided for legitimate testing, development, interoperability, maintenance, and personal use with software and content that the user owns or is authorized to access. It is not intended to facilitate piracy, unauthorized access, circumvention of access controls, cheating, abuse of online services, or infringement of third-party rights.

Users are solely responsible for how they use SteamLord and for complying with applicable laws, platform terms, software licenses, and content rights. The project is provided without any warranty that a particular use is permitted in every country or under every third-party agreement.

Nothing in this documentation grants permission to access, copy, modify, distribute, or use third-party software or content without authorization from the applicable rights holder.

## Disclaimer

SteamLord is an independent project and is not affiliated with, endorsed by, or sponsored by Valve Corporation, Steam, game publishers, or the Millennium project. Steam and related marks belong to their respective owners. Users are responsible for following all terms, licenses, and laws that apply to the software and content they use.
