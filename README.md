# Netling 2.0 test builds

Netling is a small cyberpunk pet that lives on your phone or desktop. You raise it, it changes, and it asks for attention while you are away. This repository holds test builds only. There is no source code here.

**AI disclosure.** Netling is designed and directed by a person, and its code, art data and text were written with the help of AI tools (Claude, by Anthropic). Treat everything here as a test build.

## Downloads

Pick the newest entry under **Releases**. These are pre-releases for testing, and they are not signed, so each system warns the first time.

| System | File | First run |
|---|---|---|
| Windows | `...-windows-setup.exe` (installer) or `...-windows-portable.exe` | SmartScreen: choose "More info", then "Run anyway". |
| macOS (Apple silicon) | `...-macos.dmg` | Open the disk image, drag Netling into Applications. If macOS blocks it, right-click the app and choose Open. |
| Linux | `...-linux.AppImage` | Make it executable (`chmod +x`), then run it. The tray icon needs a system tray (AppIndicator). |

Android builds are not offered yet.

## Your save

The save is a file on your computer. Installed copies keep it in the system's app-data folder. For a portable copy, put a folder named `netling-data` next to the program and it keeps everything there. Test builds may change the save format, so a new build might not read an old save.

## Tray and pet window

Closing the window hides Netling to the tray, so alerts keep arriving. The tray menu has **Pet window**, a small always-on-top view of your netling, and **Quit**.

## Feedback

Please say which system you use, what you did, and what you saw. Use **Issues** on this repository.
