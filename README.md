# ⚡ tmux-config

> A clean, modern, Powerline-inspired tmux configuration for developers who love speed, keyboard ergonomics, and statusline aesthetics.

![screenshot](https://raw.githubusercontent.com/Copxer/tmux-config/main/assets/screenshot.png)

## ✨ Features

- 🔧 Custom keybindings for pane navigation and resizing
- 🚀 Powerline-style status bar with Nerd Font icons
- 📂 Git branch display (auto-detects repo in current pane)
- 🕐 Live clock, date, uptime, load average, and hostname
- 🖱️ Mouse support (click to resize/select panes)
- ⌨️ Prefix remapped to `Ctrl + Space` for comfort (macOS-friendly)
- 🪟 Windows and panes start at index `1` for easier navigation
- 🧠 Designed to work seamlessly with Neovim and lualine-style setups

## 🔨 Keybindings

| Action                            | Keys                          |
|----------------------------------|-------------------------------|
| Prefix                           | `Ctrl + Space`                |
| Reload tmux config               | `Prefix + r`                  |
| Move between panes (Vim-style)   | `Alt + h/j/k/l`               |
| Resize panes                     | `Alt + Shift + h/j/k/l`       |
| Switch windows                   | `Alt + ← / →`                 |
| Horizontal split                 | `Alt + \`                     |
| Vertical split                   | `Alt + -`                     |

> Tip: Make sure "Use Option as Meta" is enabled in your terminal emulator.

## 🖋 Requirements

- [tmux](https://github.com/tmux/tmux) `3.1+`
- A [Nerd Font](https://www.nerdfonts.com/font-downloads) (e.g. Fira Code, Hack, JetBrainsMono)
- Terminal that supports 256-color and Unicode (iTerm2, Alacritty, WezTerm, etc.)

## 📦 Installation

1. Clone this repo:

   ```bash
   git clone https://github.com/Copxer/tmux-config ~/.tmux
   ```

2. Symlink the config:

   ```bash
   ln -s ~/.tmux/.tmux.conf ~/.tmux.conf
   ```

3. Reload tmux:

   ```bash
   tmux source-file ~/.tmux.conf
   ```

4. Enjoy your fresh tmux experience ✨

## 🧪 Font Test

Run this in your terminal:

```bash
echo ""
```

If you see beautiful arrows and separators — you're good to go!

## 🤝 Contributions

Feel free to fork and modify. PRs are welcome for:
- Bug fixes or cleaner keybindings
- Theme tweaks or additional status segments
- Cross-platform improvements (Linux, macOS)

## 📜 License

MIT © [Copxer](https://github.com/Copxer)

