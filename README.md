<p align="center"><img src="kepta-logo.svg" width="88" alt="KEPTA"></p>
<h1 align="center">KEPTA Enterprise — downloads</h1>
<p align="center"><strong>The desktop app for your AI's memory — local, encrypted, yours.</strong></p>

This repository holds the **installers** for KEPTA Enterprise — no source code. KEPTA Enterprise is proprietary software and runs with a **license key**, checked offline on your machine. There is no trial.

- **Get a license:** [write to Damian Todorovic on LinkedIn](https://www.linkedin.com/in/damian-todorovic-244235434). A key is bound to your name.
- **The open core:** the memory engine, the MCP server and the HTTP API are open source (AGPL-3.0) — [DamianTodorovic/kepta](https://github.com/DamianTodorovic/kepta). It reads the same file the app writes, so your memory never becomes a hostage of the license.

## ⬇️ Download

**[Latest release →](https://github.com/DamianTodorovic/kepta-enterprise-releases/releases/latest)**

| Your system | File |
|---|---|
| Mac with Apple silicon (M1 and later) | `KEPTA-<version>-mac-arm64.dmg` |
| Mac with an Intel processor | `KEPTA-<version>-mac-x64.dmg` |

Not sure which Mac you have? Apple menu → *About This Mac*: "Apple M…" means `arm64`, "Intel" means `x64`. Windows or Linux: [ask me](https://www.linkedin.com/in/damian-todorovic-244235434).

**Check your download.** Every release lists the SHA-256 of each file. In Terminal, `shasum -a 256 ~/Downloads/KEPTA-*.dmg` must print the same number.

## 🍎 Install on macOS

1. Open the `.dmg` and drag **KEPTA** into **Applications**.
2. Start KEPTA once. macOS says it cannot verify the developer: KEPTA is not notarised by Apple yet — that needs a paid Apple developer certificate. The app itself is signed ad hoc and unchanged; what is missing is Apple's stamp.
3. Approve it once, either way:
   - **System Settings → Privacy & Security**, scroll to the message about KEPTA, click **Open Anyway** and confirm with your password — or
   - in Terminal: `xattr -dr com.apple.quarantine /Applications/KEPTA.app`
4. Enter your name and your license key. Activation is offline.

> Older guides say to right-click the app and choose *Open*. Apple removed that route in macOS 15; use one of the two above.

## ✨ What you get

- **Knowledge graph** — Force and Tree views, a time slider back to any day
- **Capture** — drag & drop PDFs, Markdown, text and JSON; Obsidian vault import; URL clipper; a scan of your own computer with a preview first
- **Chat with your memory** — the model you choose, 20 provider presets; every answer shows which memories it used
- **Duplicate review**, **Device Sync** between your own devices, a command palette (⌘K)
- **Encrypted at rest** — SQLCipher 4, AES-256; the key lives in your macOS Keychain, with a recovery key in one click
- **One brain for every AI** — Claude Desktop, Cursor and any MCP client read and write the same memory

## 🔒 Privacy

Everything stays on your computer, in one encrypted file: `~/.kepta/kepta.db`. No account, no telemetry — KEPTA never phones home, not even to check the license.

## 📄 License

KEPTA Enterprise is proprietary — see [LICENSE](LICENSE). Third-party components and their licenses: [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
