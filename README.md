# 🧠 PhraseSync – Smart Auto-Linker for Obsidian

**PhraseSync** is an Obsidian plugin that automatically suggests internal links as you type, matching:
- Note **titles**
- Note **headings** (`#`)
- Block **references** (`^block-id`)

No special syntax or prefix needed — it works **mid-sentence**, recognizes **multi-word phrases**, **case-insensitive**, and adapts in **real-time** as your vault evolves.

---

## ✨ Features

- 🔍 Real-time auto-suggestions for internal linking
- 🧭 Matches across titles, headings, and blocks
- 🪄 Smart phrase recognition (e.g., "French Revolution")
- ⚡ Live indexing (no manual refresh required)
- 🧠 Works anywhere in your note (not just at the beginning of a line)
- 🛠️ Clean, safe, TypeScript-based

---

## 📦 Installation

### Manual Installation

1. Download the latest `main.js`, `manifest.json`, and `styles.css` from the [Releases](https://github.com/digvijay-s-todiwal/phrasesync/releases) page.
2. Place them inside a folder named `phrasesync` in your Obsidian `.obsidian/plugins/` directory.
3. Enable the plugin from Obsidian Settings → Community Plugins.

---

## 🧪 Development

To build locally:

```bash
npm i
npm run build
