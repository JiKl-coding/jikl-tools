# jikl-tools

Small tools by JiKl: desktop apps, scripts, mobile apps and whatever else comes along. This repository hosts their
**release packages** only. Tools that can update themselves check it for new versions.

## Tools

| Tool | What it is | Platform | Releases |
| --- | --- | --- | --- |
| [jikl-hotkeys](#jikl-hotkeys) | Hotkeys that type logins, secrets and snippets into the right window | Windows | [`jikl-hotkeys/…`](https://github.com/JiKl-coding/jikl-tools/releases?q=jikl-hotkeys&expanded=true) |

### jikl-hotkeys

Press a shortcut such as `Alt+F1` in your VPN client and it types the username, presses Tab, types the password and
presses Enter. Passwords are encrypted with Windows DPAPI. One `.exe`, no administrator rights.

1. Download `jikl-hotkeys-<version>-win-x64.zip` from the newest `jikl-hotkeys/v…` release.
2. Right-click the zip → **Properties** → tick **Unblock** → OK (avoids SmartScreen blocks).
3. Extract it anywhere and run `jikl-hotkeys.exe`. It offers to install itself for your Windows user
   (`%LOCALAPPDATA%\jikl-tools\jikl-hotkeys\`, desktop and Start menu shortcuts, uninstall in **Settings → Apps**).

The app looks for new releases here and offers to update itself; it verifies the `.sha256` checksum before installing.
The full manual is the `README.md` inside the zip.

## Releases

- Every tool has its own tag prefix: `<tool>/v<version>`, e.g. `jikl-hotkeys/v1.0.0`. Filter the
  [releases](https://github.com/JiKl-coding/jikl-tools/releases) by the tool name to see only its versions.
- Packages come with a `.sha256` checksum where it makes sense; compare it before running something you downloaded.
