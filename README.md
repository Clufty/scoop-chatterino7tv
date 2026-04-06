<div align="center">

# 🟣 scoop-chatterino7tv

A [Scoop](https://scoop.sh) bucket for **Chatterino 7TV** — a Twitch chat client with native [7TV](https://7tv.app) emote, paint, badge, and cosmetic support.

The official portable build doesn't auto-update, so this bucket tracks the nightly and handles it for you.

> ⚠️ **Rename in progress** — This project is being renamed from *Chatterino7* to *Chatterino 7TV*, with the version scheme changing from `7.x.y` → `2.x.y`. The manifest will be updated as changes land upstream. See [SevenTV/chatterino7#323](https://github.com/SevenTV/chatterino7/issues/323).

---

by **Cluft** &nbsp;·&nbsp; `Cluft` on Discord & 7TV &nbsp;·&nbsp; [`Clufti`](https://twitch.tv/Clufti) on Twitch &nbsp;·&nbsp; [`Clufty`](https://github.com/Clufty) on GitHub

</div>

---

## Requirements

- Windows 10 or later (x86-64)
- [Scoop](https://scoop.sh) installed

## Install

**1. Install Scoop** (skip if you already have it):
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
irm get.scoop.sh | iex
```

**2. Add this bucket:**
```powershell
scoop bucket add chatterino7tv https://github.com/Clufty/scoop-chatterino7tv
```

**3. Install:**
```powershell
scoop install chatterino7tv/chatterino7tv
```

## Update
```powershell
scoop update chatterino7tv
```

To update everything at once:
```powershell
scoop update *
```

## Uninstall
```powershell
scoop uninstall chatterino7tv
```

---

## Notes

- **Portable mode** — config is stored next to the exe in `~\scoop\apps\chatterino7tv\current\`, not in AppData. Your settings survive updates.
- **Versioning** — the version string looks like `6.9.3-202604051423` (Qt version + build timestamp). It changes with every nightly push, which is how Scoop detects that an update is available.
- **Hash skipping on updates** — the nightly release reuses the same URL with new content on each build, and no checksums file is published alongside it, so hash verification is skipped for updates. The initial install hash is pinned.

## Disclaimer

This bucket is **unofficial** and unaffiliated with SevenTV or the Chatterino project.
For bugs or issues with Chatterino 7TV itself, please report them [upstream](https://github.com/SevenTV/chatterino7/issues).

---

<div align="center">

Chatterino 7TV is [MIT licensed](https://github.com/SevenTV/chatterino7/blob/chatterino7/LICENSE) © the Chatterino contributors.
The manifests in this bucket are likewise released under [MIT](LICENSE).

</div>
