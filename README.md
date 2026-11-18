# jikl-tools

Small Windows tools by JiKl. This repository hosts their **release packages** only; the tools check it for new
versions and update themselves from here.

## jikl-hotkeys

Hotkeys that type your logins, secrets and snippets into the right window. Press a shortcut such as `Alt+F1` in your
VPN client and it types the username, presses Tab, types the password and presses Enter. Passwords are encrypted with
Windows DPAPI. One `.exe`, no administrator rights.

**[Download → releases tagged `jikl-hotkeys/…`](https://github.com/JiKl-coding/jikl-tools/releases?q=jikl-hotkeys&expanded=true)**

1. Download `jikl-hotkeys-<version>-win-x64.zip` from the newest `jikl-hotkeys/v…` release.
2. Right-click the zip → **Properties** → tick **Unblock** → OK (avoids SmartScreen blocks).
3. Extract it anywhere and run `jikl-hotkeys.exe`. It offers to install itself for your Windows user
   (`%LOCALAPPDATA%\jikl-tools\jikl-hotkeys\`, Start menu shortcut, uninstall in **Settings → Apps**).

From version 1.1.0 on, the app looks for new releases here and offers to update itself. Each package comes with a
`.sha256` checksum, which the app verifies before installing an update. The full manual is the `README.md` inside the zip.

## Release tags

Every tool has its own tag prefix: `<tool>/v<version>`, e.g. `jikl-hotkeys/v1.1.0`.
