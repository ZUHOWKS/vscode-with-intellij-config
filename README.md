# VSCode with IntelliJ Config

Bring the IntelliJ IDEA developer experience into **VSCode** — this repository provides keybindings and settings to help you feel right at home with JetBrains-style shortcuts and behaviors.

This configuration is compatible with **Cursor** and **Windsurf**.

## 📦 What's Included

- `keybindings.json` — Custom keyboard shortcuts (e.g., `Cmd+W` for smart inline selection)
- `settings.json` — Recommended editor settings (e.g., tab behavior, UI tweaks, autosave)

## 📥 Installation

1. Open **VSCode**, **Cursor** or **Windsurf**.
2. Open the command palette (`Cmd+Shift+P` or `Ctrl+Shift+P`) and search for `Preferences: Open Keyboard Shortcuts (JSON)`.
3. Copy-paste the contents of `keybindings.json` from this repository.
4. Open `Preferences: Open User Settings (JSON)` the same way.
5. Copy-paste the contents of `settings.json`.

Alternatively, you can manually replace both files in:

- macOS/Linux: `~/.config/Code/User/`
- Windows: `%APPDATA%\Code\User\`

## 💡 Tips

- You can combine this config with the [IntelliJ IDEA Keybindings extension](https://marketplace.visualstudio.com/items?itemName=k--kato.intellij-idea-keybindings) for a more complete feel.
- Adjust the settings as needed for themes, fonts, or editor behavior.

## 🙌 Contributions

Feel free to open an issue or PR if you'd like to tweak the config or add JetBrains-like behaviors.
