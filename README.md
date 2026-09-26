# p3-defense
thesis
# Genshin Impact Wish Simulator – Browser Extension

A free, offline Genshin Impact Wish Simulator that runs as a **Chrome / Edge / Firefox** browser extension.

No installation of extra software needed — just load the extension and start wishing.

---

## Features

- All banner types (Beginner, Standard, Character Event, Weapon Event)
- Realistic pity system (soft pity + hard pity)
- Epitomized Path support
- Inventory, Wish History, and Pity counter
- Shop (Starglitter / Stardust exchange, Welkin, Outfits)
- Fully offline after installation
- Data saved locally (IndexedDB + localStorage)
- Mobile-friendly layout (works in extension popup or full tab)

---

## Installation (Developer Mode)

### Chrome / Edge / Brave / Opera

1. Download or clone this repository
2. Open the browser and go to:
   - Chrome → `chrome://extensions`
   - Edge → `edge://extensions`
3. Enable **Developer mode** (top-right toggle)
4. Click **Load unpacked**
5. Select the `build` folder (the folder that contains `manifest.json`)

### Firefox

1. Go to `about:debugging#/runtime/this-firefox`
2. Click **Load Temporary Add-on**
3. Select the `manifest.json` file inside the `build` folder

---

## How to Use

- Click the extension icon in the toolbar to open the simulator (popup mode)
- Or open it as a full page / new tab (depending on how you configured the manifest)

All your pity, inventory, and history are saved automatically on your device.

---

## Development

### Prerequisites
- Node.js 18+ 
- npm / yarn / pnpm

### Setup

```bash
git clone https://github.com/YOUR_USERNAME/Genshin-Impact-Wish-Simulator.git
cd Genshin-Impact-Wish-Simulator
npm install
