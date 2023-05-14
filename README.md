# ***penguinVim***

---



![CodeFactor Grade](https://img.shields.io/codefactor/grade/github/p3nguin-kun/penguinVim?color=d65d0e&style=for-the-badge)
![lmao](https://img.shields.io/github/repo-size/p3nguin-kun/penguinVim?color=458588&style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/p3nguin-kun/penguinVim?color=ebdbb2&style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/p3nguin-kun/penguinVim?color=cc241d&style=for-the-badge)
![GitHub pull requests](https://img.shields.io/github/issues-pr/p3nguin-kun/penguinVim?color=689d6a&style=for-the-badge)

---

*NeoVim but better*

***penguinVim is a NeoVim config written in Lua aiming to provide a base configuration with beautiful UI and fast startuptime (around 0.02 secs ~ 0.07 secs)***


---

## 📑 ***Menu***

- [✨ Features](#features)
- [⚡ Requirements](#requirements)
- [🛠️ Installation](#installation)

## ✨ ***Features***

- 🔥 Transform your Neovim into a full-fledged IDE
- 💤 Easily customize and extend your config with [lazy.nvim](https://github.com/folke/lazy.nvim)
- 🚀 Blazingly fast
- 🧹 Sane default settings for options, autocmds, and keymaps
- 📦 Comes with a wealth of plugins pre-configured and ready to use

---

## ⚡️ ***Requirements***

- Neovim >= **0.8.0** (needs to be built with **LuaJIT**)
- Git >= **2.19.0** (for partial clones support)
- a [Nerd Font](https://www.nerdfonts.com/) **_(optional)_**

---

## 🛠️ ***Installation***
1. First, you need to install nvim and git

- Arch Linux and Arch-based distro:
```
sudo pacman -S neovim git
```

- Debian and Debian-based distro:
```
sudo apt install neovim git
```

- Fedora and Red-hat based distro:
```
sudo dnf install neovim git
```
- macOS:
```
brew install neovim (if you use macOS)
```

- Termux:
```
pkg install neovim git (if you use Termux)
```

2. Install penguinVim
```
git clone https://github.com/p3nguin-kun/penguinVim ~/.config/nvim
```

3. Go to ```nvim``` and install plugins
```
nvim
```
