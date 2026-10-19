# Claude Buddy

[![Support on Ko-fi](https://img.shields.io/badge/Support-Ko--fi-FF5E5B?logo=ko-fi&logoColor=white)](https://ko-fi.com/seankealey)

A little pixel-art desktop pet for Windows that lives on your **Claude Code** usage. It hatches from an egg, eats the
tokens you spend, levels up through seven life stages, and gets hungry if you leave it alone for too long.

![Claude Buddy growing up](images/hero.gif)

It also keeps an eye on things while you work: tokens and cost today, how much of your 5-hour and weekly limits
you've used, and a pixel "!" when a Claude Code session is waiting on you (click it to jump to that terminal).

![The classic buddy at every life stage](images/common-characters.png)

Every buddy is rolled when its egg is laid. Some buddies are… rarer than others. You'll know one when you see it.

## Requirements

- Windows 10 or 11
- Claude Code: the CLI, or the Code tab in the Claude desktop app

## Install

1. Download `ClaudeBuddy-Setup-<version>.exe` from the
   [latest release](https://github.com/skealeye/ClaudeBuddy-releases/releases/latest).
2. Run it. No admin rights needed: it installs just for you.
3. **"Windows protected your PC"?** The installer isn't code-signed yet. Click **More info**, then **Run anyway**.
4. Your buddy appears in the corner of the screen. Open its **Settings** page (drag sideways or use the dots) and
   click **Connect** so it can see your Claude Code sessions.

## Updates

Claude Buddy keeps itself up to date: it checks once a day, downloads a new version quietly and installs it when
none of your Claude Code sessions is busy. Prefer to choose? Turn off **Auto updates** in Settings: the tray menu
then shows **Update to … available**, and **Check for updates…** looks right away. Updates are signed, and Claude
Buddy only installs updates signed by its author.

## Privacy

Claude Buddy reads Claude Code's own files on your PC and keeps everything on your PC: no account, no telemetry.
Its only network calls are the live weather (Open-Meteo, for your Windows location or a city you type) and the update
check (GitHub).

## Uninstall

Windows Settings → Apps → Installed apps → **Claude Buddy** → Uninstall. This also removes its hooks from Claude
Code. You can keep your buddy and graveyard (the default) or delete them.

## What's new

### 2.0.2

- A **Restart** item in the tray menu.
- Settings shows the game-balance number with the version, like `v2.0.2.b2`.
- Safer updates: each installer's signature is now tied to its version, and Install now always installs the newest
  release.
- Uninstalling on a PC that never ran Claude Buddy no longer leaves an empty folder behind.

### 2.0.1

The About link in Settings no longer runs into the Location row on a wide card, and the whole
line is easy to click.

### 2.0.0

The first public release: a one-click installer, automatic updates, and a buddy that lives on your Claude Code
usage.

## Support

Claude Buddy is free. If it makes your day a little better, you can
[buy me a coffee on Ko-fi](https://ko-fi.com/seankealey). ♥

Made by Sean Kealey (Digitalpirate).

---

Claude Buddy is an unofficial fan project. It is not affiliated with, endorsed by, or sponsored by Anthropic.
Claude is a trademark of Anthropic.

Weather data by [Open-Meteo.com](https://open-meteo.com/) (CC BY 4.0). Claude Buddy's licence is in
[LICENSE.txt](LICENSE.txt); the open-source components it uses are listed in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
