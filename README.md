# DiscUpdater - BetterDiscord Installer and Updater

DiscUpdater is a simple tool that automatically downloads and installs the latest version of BetterDiscord for Discord. It works as both an installer (if BetterDiscord isn't installed) and an updater (to get the latest version).

## Requirements
- Windows operating system
- Internet connection
- PowerShell (usually pre-installed on Windows)

## How to Use

1. Download the files:
   - `DiscUpdater.bat`
   - `DiscUpdater.ps1`

2. Place both files in the same folder on your computer.

3. Run the tool:
   - Double-click `DiscUpdater.bat` to start the process.
   - The batch file will execute the PowerShell script automatically.

4. Follow the on-screen instructions:
   - The tool will fetch the latest BetterDiscord installer from GitHub.
   - It will download and run the installer.
   - After installation, it will clean up temporary files.

5. Restart Discord if it's open to apply the changes.

## What It Does
- Fetches the latest BetterDiscord release from GitHub.
- Downloads the installer executable.
- Runs the installer to install or update BetterDiscord.
- Moves the installer to the trash bin after use.
- Cleans up any leftover .asar files.

If the tool encounters any issues, it will provide instructions to download manually from https://betterdiscord.app.

## Troubleshooting
- If you get an error, try running as administrator.
- Ensure your internet connection is stable.
- Check that Discord is closed during installation.
