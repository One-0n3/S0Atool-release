# SOATool — releases

SOATool is a Windows modding toolkit for Ghost Recon Breakpoint.
This repository distributes compiled test builds.

## Download

Open [Releases](https://github.com/One-0n3/S0Atool-release/releases) and choose:

- **Installer:** `SOAtool_Setup_v4.2.exe`.
- **Portable:** `SOAtool_v4.2_portable.zip`. Extract the complete archive before running `SOAtool.exe`.
- **Checksums:** `SHA256SUMS.txt`, for verifying downloaded files.

## Discord access

Downloading the files does not grant application access. To use SOATool:

1. Belong to the SOA community Discord server.
2. Receive the **SOATOOL** role from the server owner.
3. Start SOATool and choose **Sign in with Discord**.
4. Authorize the same Discord account that holds the role.

The app checks server membership and the role during use. Removing the role
or leaving the server removes access at the next verification. An internet
connection is required for sign-in and periodic verification.

## Test build notes

- First launch on a fresh Windows profile starts with an empty notebook.
- Your own existing local notes are preserved when updating.
- This version asks you to sign in again after restarting the application.
- Windows WebView2 and .NET 9 are required. Install the applicable Microsoft
  runtimes if the application cannot start on your test machine.
- These initial test builds do not have an Authenticode code-signing certificate.
- Work on copies of your mod files while testing. Report startup problems and
  tool errors to the project owner through the community Discord.

No source code, Discord credentials, user notes or debug symbols are published here.
