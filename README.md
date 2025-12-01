# Pokemon Auto Chess Live Data Calculator

A Chrome extension that provides real-time probability calculations for [Pokemon Auto Chess](https://pokemon-auto-chess.com).

![Version](https://img.shields.io/badge/version-3.1.1-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Features

### 🎯 Main Calculator
- **Per-refresh probability** for finding your target Pokemon
- **Expected rolls** to hit your desired confidence level
- **Gold cost estimation** based on your roll strategy
- **Pool tracking** showing copies remaining vs total

### 🌍 Smart Pokemon Detection
- **Hover-to-detect** regional and add pick Pokemon from game icons
- **Conflict resolution** — click to confirm when multiple Pokemon match (e.g., Pidgey/Starly/Pidove)
- **Auto-sync** detection results to probability calculations
- **Wild handling** — wild regionals/additionals update correct pool counts

### 📊 Counter Intelligence Panel
- See all 8 players' boards, benches, and shops at a glance
- **Contested detection** — warns when opponents are targeting the same Pokemon
- **Flash alerts** when your target appears in YOUR shop

### 🎯 Team Tracker
- Track multiple target Pokemon simultaneously
- **MAXED / IMPOSSIBLE / DANGER** warnings for each target
- **Regional/Portal availability** checking
- Progress tracking with copies owned vs needed

### 🌿 Wild Pokemon Support
- **Auto-detects** all 67 wild Pokemon families
- **Counts wild stars** automatically (3★ = +3% boost)
- **Per-rarity pool tracking** — accurate probability calculations
- **PVE round detection** for +5% wild boost

### 🎰 Mono-Type Challenge (Experimental)
- **Self-imposed challenge mode** — restrict yourself to one Pokemon type
- **Spin wheel** for random type selection
- **Shop blockers** prevent purchasing non-matching types
- 18 types available with color-coded UI

### ⚡ Live Data
- Reads game state in real-time (30ms polling)
- Stage tracking with PVE/PVP indicator
- Auto-updates as the game progresses
- Works entirely offline — **zero data transmitted**

## Installation

### Chrome Web Store
*Coming soon — pending review*

### Manual Installation

1. **Download** the latest ZIP from [Releases](../../releases)
2. **Extract** the ZIP to a folder
3. Open Chrome and go to `chrome://extensions`
4. Enable **Developer mode** (top-right toggle)
5. Click **"Load unpacked"** and select the extracted folder
6. Navigate to [pokemon-auto-chess.com](https://pokemon-auto-chess.com)
7. Press **P** to toggle the calculator

## Usage

1. Go to [pokemon-auto-chess.com](https://pokemon-auto-chess.com)
2. Start or join a game
3. Press **P** to toggle the calculator overlay
4. Enter your player name for personalized tracking
5. Select your target Pokemon and rarity
6. **Hover** the regional/add pick icons to detect Pokemon
7. **Click** to resolve conflicts when multiple Pokemon match

## Controls

| Control | Action |
|---------|--------|
| P | Toggle calculator overlay |
| CLR button | Clear all state (target, team, detection) |
| Redetect button | Reset detection for new portal |
| Hover game icons | Detect regional/add pick Pokemon |

## Privacy

This extension:
- ✅ Runs entirely locally
- ✅ Makes **zero** network requests
- ✅ Stores preferences in localStorage only
- ✅ Never collects or transmits any data

See [PRIVACY.md](PRIVACY.md) for full details.

## Support

- **Discord:** @Deuce222X
- **Issues:** [GitHub Issues](../../issues)

## Changelog

### v3.1.1 — Mono-Type Challenge + Manifest Cleanup
- **NEW:** Mono-Type Challenge mode (experimental) — restrict shop to one Pokemon type
- **NEW:** Spin wheel for random type selection with animation
- **NEW:** Shop blockers with fixed positioning (blocks tooltips properly)
- **FIX:** Removed unnecessary `host_permissions` from manifest
- **FIX:** Petilil, Cubone, Exeggcute, Slowpoke now correctly detected as Add Picks
- **FIX:** Galarian Slowpoke regional detection

### v3.0.0 — Major Release
- **FIX:** Critical wild pool tracking bug — now tracks per-rarity (was depleting wrong pools)
- **FIX:** Detection listeners reset properly between games (multi-game sessions work)
- **NEW:** Synergy bar for mass team building (experimental feature)
- **NEW:** Experimental features system with unlock
- **NEW:** Ditto stage-gating (available from Stage 6+)
- **IMPROVED:** MAX polling speed now 30ms
- **IMPROVED:** Blocker dismiss remembers dismissed Pokemon until they leave shop

### v2.19.0 — Smart Detection System
- **NEW:** Slot-based regional/add pick detection with conflict resolution
- **NEW:** Click-to-confirm when multiple Pokemon match same rarity+types
- **NEW:** Detection syncs to probability calculations
- **NEW:** Team Tracker checks regional/additional availability
- **NEW:** CLR button to clear all state
- **NEW:** Redetect button for new portals
- **FIX:** Wild regionals/additionals now update correct pool counts
- **FIX:** CLR properly clears evolution family display

### v2.18.0 — Regional & Portal Detection
- **NEW:** Hover-based detection from game icons
- **NEW:** Pokemon chips with rarity colors
- **IMPROVED:** Simplified UI with accordion removal

### v2.17.0 — Wild Pokemon Overhaul
- Wild Pokemon auto-detection (67 families)
- Wild stars counting fix
- Auto-scout opponents' wild copies
- PVE round auto-detection
- Main calculator MAXED/IMPOSSIBLE/DANGER warnings
- Fixed contested detection to exclude self
- Name normalization for regional forms

### v2.16.0 — Counter Intelligence & Team Tracker
- Counter Intelligence panel
- Team Tracker with multi-target support
- Shop flash alerts
- Keyboard input protection

## Credits

**Developer:** Galliano Games (DonaldGallianoIII)

Built for the Pokemon Auto Chess community 🎮

## License

MIT License — feel free to fork and modify!
