## [1.3.0] – YYYY-MM-DD

### 🚀 New Features

- **Configurable reload trigger**  
	- Added a ribbon-icon button to manually reload PhraseSync at any time.  
	- Exposed a “Reload PhraseSync” command in the Command Palette, with a placeholder hotkey.
	- Users can now assign their own shortcut: navigate to **Settings → Community plugins → PhraseSync**, click the **+** next to “Reload PhraseSync,” and define any key combination.

### 🔧 Technical Details

- **Ribbon icon integration**  
	- Uses Obsidian’s `addRibbonIcon('refresh-cw', …)` API.  
	- Invoking the icon calls `safeReload()`, with status-bar feedback and a native `Notice`.

- **Hotkey customization**  
	- Registered the reload command (`id: 'reload-phrasesync'`) without a hard-coded key binding.  
	- Leverages Obsidian’s settings UI to allow users to bind any desired hotkey, improving flexibility and avoiding conflicts.