# Pokemon Auto Chess Live Data Calculator

A Chrome extension that provides real-time probability calculations for [Pokemon Auto Chess](https://pokemon-auto-chess.com).

![Version](https://img.shields.io/badge/version-2.17.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Features

### 🎯 Main Calculator
- **Per-refresh probability** for finding your target Pokemon
- **Expected rolls** to hit your desired confidence level
- **Gold cost estimation** based on your roll strategy
- **Pool tracking** showing copies remaining vs total

### 📊 Counter Intelligence Panel
- See all 8 players' boards, benches, and shops at a glance
- **Contested detection** - warns when opponents are targeting the same Pokemon
- **Flash alerts** when your target appears in YOUR shop

### 🎯 Team Tracker
- Track multiple target Pokemon simultaneously
- **MAXED / IMPOSSIBLE / DANGER** warnings for each target
- Progress tracking with copies owned vs needed

### 🌿 Wild Pokemon Support
- **Auto-detects** all 67 wild Pokemon families
- **Counts wild stars** automatically (3★ = +3% boost)
- **Scouts opponents'** wild copies for accurate pool depletion
- **PVE round detection** for +5% wild boost

### ⚡ Live Data
- Reads game state in real-time
- Stage tracking with PVE/PVP indicator
- Auto-updates as the game progresses
- Works entirely offline - **zero data transmitted**

## Installation

### Chrome Web Store (Recommended)
*Coming soon - pending review*

### Manual Installation (Beta Testing)
See [INSTALL.md](INSTALL.md) for step-by-step instructions.

## Usage

1. Go to [pokemon-auto-chess.com](https://pokemon-auto-chess.com)
2. Start or join a game
3. Press **ALT + Shift + P** to toggle the calculator overlay
4. Enter your player name for personalized tracking
5. Select your target Pokemon and rarity

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| ALT + Shift + P | Toggle calculator overlay |

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

### v2.17.0
- Wild Pokemon auto-detection (67 Pokemon families)
- Wild stars counting (was counting units, now correctly counts stars)
- Auto-scout opponents' wild copies
- PVE round auto-detection
- Main calculator MAXED/IMPOSSIBLE/DANGER warnings
- Fixed contested detection to exclude self
- Name normalization for regional forms

### v2.16.0
- Counter Intelligence panel
- Team Tracker with multi-target support
- Shop flash alerts
- Keyboard input protection

## Credits

**Developer:** Galliano Games (DonaldGallianoIII)

Built for the Pokemon Auto Chess community 🎮

## License

MIT License - feel free to fork and modify!
