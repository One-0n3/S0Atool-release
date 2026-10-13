# SOATool — Official Releases

[![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D6?logo=windows&logoColor=white)](#system-requirements)
[![.NET](https://img.shields.io/badge/.NET%20Desktop%20Runtime-9.0-512BD4?logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
[![Status](https://img.shields.io/badge/Build-Test%20Release-orange)](#release-notes--known-behaviors)

**SOATool** is a specialized Windows modding toolkit for *Tom Clancy's Ghost Recon Breakpoint*. 

This repository serves exclusively as the official distribution channel for compiled test builds. No source code, user data, credentials, or debug symbols are hosted here.

---

## Installation & Downloads

Visit the [**Releases**](https://github.com/One-0n3/S0Atool-release/releases) page to download the latest build (`v4.2`):

| Package Type | File Name | Description & Instructions |
| :--- | :--- | :--- |
| **Installer** | `SOAtool_Setup_v4.2.exe` | Standard Windows installer. Recommended for most users. |
| **Portable** | `SOAtool_v4.2_portable.zip` | Standalone archive. **Extract all files** to a folder before running `SOAtool.exe`. |
| **Checksums** | `SHA256SUMS.txt` | SHA-256 hashes for verifying file integrity after download. |

---

## System Requirements

Ensure the following dependencies are installed on your system before launching **SOATool**:

* **[.NET Desktop Runtime 9.0 (Windows x64)](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)** — *Make sure to install the **Desktop Runtime**, which includes the base .NET runtime.*
* **[Microsoft Edge WebView2 Runtime](https://developer.microsoft.com/en-us/microsoft-edge/webview2)** — *Pre-installed on most modern Windows systems, but required for UI rendering.*
* **Active Internet Connection** — *Required for initial Discord OAuth2 authentication and periodic access verification.*

---

## Access & Authentication

> [!IMPORTANT]
> Downloading the application files **does not** automatically grant access to SOATool. Access is restricted to verified community members.

### How to Authenticate:
1. Join the **SOA Community Discord** server.
2. Obtain the **`SOATOOL`** role from the server owner.
3. Launch **SOATool** and click **Sign in with Discord**.
4. Authorize the application using the exact Discord account that holds the **`SOATOOL`** role.

*Note: SOATool actively verifies server membership and role status during use. Leaving the server or losing the required role will automatically revoke application access upon the next verification check.*

---

## Release Notes & Known Behaviors

Please keep the following points in mind while working with these test builds:

* **Local Data & Updates:** Launching the tool for the first time on a fresh Windows profile initializes an empty notebook. Your existing local notes are safely preserved when updating to a newer version.
* **Session Persistence:** Current test builds require you to sign in with Discord again each time you restart the application.
* **Code Signing:** These initial test builds do not carry an Authenticode code-signing certificate (Windows SmartScreen may display a warning on first launch).

> [!CAUTION]
> **Backup Your Files:** Because this is a test build, always work on **backups/copies** of your mod files. Please report any startup issues, crashes, or tool errors directly to the project owner via the SOA Community Discord.
