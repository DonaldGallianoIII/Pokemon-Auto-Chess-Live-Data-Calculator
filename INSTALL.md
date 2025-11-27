# Manual Installation Guide

Install the PAC Live Data Calculator before it's available on the Chrome Web Store.

---

## Step 1: Download the Extension

1. Go to the [**Pokemon Auto Chess Live Data Calculator ZipFile**](Pokemon%20Auto%20Chess%20Live%20Data%20Calculator%20ZipFile/) folder in this repo
2. Click on the `.zip` file (e.g., `pac-live-data-v2_17_0-store-ready GITHUB.zip`)
3. Click the **Download** button (or "View raw")
4. Save the file to your computer

---

## Step 2: Extract the ZIP File

### Windows
1. Find the downloaded ZIP in your Downloads folder
2. Right-click the file → **Extract All...**
3. Choose a location (Desktop is fine) → Click **Extract**

### Mac
1. Find the downloaded ZIP in your Downloads folder
2. Double-click the file (it auto-extracts)

### Linux
```bash
unzip pac-live-data-v2_17_0-store-ready.zip -d pac-extension
```

**After extraction, you should have a folder containing:**
```
├── manifest.json
├── content/
│   ├── overlay.js
│   └── extractor.js
└── icons/
    ├── icon16.png
    ├── icon48.png
    └── icon128.png
```

---

## Step 3: Enable Developer Mode in Chrome

1. Open **Google Chrome**
2. Type `chrome://extensions` in the address bar
3. Press **Enter**
4. Toggle **Developer mode** ON (top-right corner)

---

## Step 4: Load the Extension

1. Click **"Load unpacked"** (top-left of the extensions page)
2. Navigate to your **extracted folder** (the one containing `manifest.json`)
3. Click **Select Folder**

✅ You should now see "Pokemon Auto Chess Live Data Calculator" in your extensions list!

---

## Step 5: Test It Out

1. Go to [**pokemon-auto-chess.com**](https://pokemon-auto-chess.com)
2. Start or join a game
3. Press **Alt + Shift + P** to open the calculator
4. Enter your player name in settings
5. Start tracking!

---

## Updating to a New Version

When a new version is released:

1. Download the new ZIP file
2. Extract it (you can replace the old folder)
3. Go to `chrome://extensions`
4. Find "Pokemon Auto Chess Live Data Calculator"
5. Click the **↻ refresh icon** on the extension card

---

## Troubleshooting

| Problem | Solution |
|---------|----------|
| "Load unpacked" button not visible | Make sure **Developer mode** is ON |
| Extension not appearing on game | Refresh the game page (F5) |
| Data not updating | Check that your player name matches exactly (case-sensitive) |
| Extension shows error | Make sure you selected the folder containing `manifest.json`, not the ZIP file |

---

## Uninstalling

1. Go to `chrome://extensions`
2. Find "Pokemon Auto Chess Live Data Calculator"
3. Click **Remove**

---

## Questions?

**Discord:** @Deuce222X

Found a bug? [Open an issue](../../issues) on GitHub!
