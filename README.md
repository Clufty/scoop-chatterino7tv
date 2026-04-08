<div align="center">

# 🟣 scoop-chatterino7tv

**Chatterino 7TV** — auto-updating Scoop bucket for the nightly build

A [Scoop](https://scoop.sh) bucket for [Chatterino 7TV](https://github.com/SevenTV/chatterino7) — a Twitch chat client with native [7TV](https://7tv.app) emote, paint, badge, and cosmetic support. The official [nightly build](https://github.com/SevenTV/chatterino7/releases/tag/nightly-build) doesn't auto-update, so this bucket tracks it and handles that for you.

[![Nightly](https://img.shields.io/badge/tracks-nightly%20build-blueviolet?style=flat-square)](https://github.com/SevenTV/chatterino7/releases/tag/nightly-build)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Auto-update](https://img.shields.io/badge/auto--update-every%206h-success?style=flat-square)](https://github.com/Clufty/scoop-chatterino7tv/actions)

> ⚠️ **Rename in progress** — This project is being renamed from *Chatterino7* to *Chatterino 7TV*, with the version scheme changing from `7.x.y` → `2.x.y`. The manifest will be updated as changes land upstream. See [SevenTV/chatterino7#323](https://github.com/SevenTV/chatterino7/issues/323).

---

[`Cluft`](https://7tv.app/users/01GTEW3G1G0001GW3P40Z5GQAV) on 7TV &nbsp;·&nbsp; `Cluft` on Discord &nbsp;·&nbsp; [`Clufti`](https://twitch.tv/Clufti) on Twitch &nbsp;·&nbsp; `Cluft` on Kick

</div>

---

## ✅ Requirements

- Windows 10 or later (x86-64)
- PowerShell 5 or later

---

## 📦 Install

Open **PowerShell** and run the following commands:

**1. Install Scoop** *(skip if you already have it)*

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex
```

**2. Add this bucket**

```powershell
scoop bucket add chatterino7tv https://github.com/Clufty/scoop-chatterino7tv
```

**3. Install Chatterino 7TV**

```powershell
scoop install chatterino7tv/chatterino7tv
```

---

## 🔄 Update

Update everything at once *(recommended)*:

```powershell
scoop update *
```

Or update only Chatterino 7TV:

```powershell
scoop update chatterino7tv
```

---

## 🗑️ Uninstall

```powershell
scoop uninstall chatterino7tv
```

---

## 📝 Notes

> **Settings** — Config is stored in `%APPDATA%\Chatterino2` and will persist across updates and uninstalls.

> **Auto-updates** — A GitHub Action checks for new nightly builds every 6 hours and updates the manifest automatically. Just run `scoop update *` to get the latest.

---

## ⚠️ Disclaimer

This bucket is **unofficial** and unaffiliated with SevenTV or the Chatterino project. For bugs or issues with Chatterino 7TV itself, please report them [upstream](https://github.com/SevenTV/chatterino7/issues).

---

<div align="center">

Chatterino 7TV is [MIT licensed](https://github.com/SevenTV/chatterino7/blob/chatterino7/LICENSE) © the Chatterino contributors.
The manifests in this bucket are likewise released under [MIT](LICENSE).

</div>
