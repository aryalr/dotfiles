# 🔧 My Dotfiles

![Work in Progress](https://img.shields.io/badge/Status-Work_in_Progress-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

Welcome to my personal collection of dotfiles! This repository houses the configuration files for my development environment and system customization. It is a living project that I will be updating and expanding as I refine my workflow.

[🇮🇩 Bahasa Indonesia](#-dotfiles-saya-indonesian)

---

## 🚀 What's Inside?

Currently, this repository includes configurations for:

- **🐚 Zsh**: My shell setup, powered by [Oh My Zsh](https://ohmyz.sh/), including custom plugins and themes.
- **🖥️ Hyprland**: Tiling window manager configurations (`hyprland.conf`, keybindings, and window rules).
- **📝 Neovim**: My text editor configuration based on [LazyVim](https://www.lazyvim.org/).
- **bar Waybar**: Status bar configuration for the Wayland compositor.
Note: Currently using HYDE for preconfigured other dotfiles. planning to use fully custom dotfiles for everythings!

## 📂 Structure

```text
/
├── .zshrc           # Zsh configuration file
├── .oh-my-zsh/      # Oh My Zsh framework and plugins
├── hyprland/        # Hyprland window manager configs
├── nvim/            # Neovim (LazyVim) configurations
└── waybar/          # Waybar style and config
```

## 🛠️ Installation

> ⚠️ **Note:** Always backup your existing configurations before applying new ones.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/dotfiles.git ~/dotfiles
    ```

2.  **Symlink the files:**
    You can manually symlink the files to their respective locations, or use a tool like GNU Stow.

    *Example for Zsh:*
    ```bash
    ln -s ~/dotfiles/.zshrc ~/.zshrc
    ```

    *Example for Neovim:*
    ```bash
    ln -s ~/dotfiles/nvim ~/.config/nvim
    ```

## 🔮 Future Plans

I plan to add configurations for more tools as I adopt them, including:
- Terminal emulators (Kitty/Alacritty)
- Tmux
- Git configurations
- And more!

---

# 🇮🇩 Dotfiles Saya (Indonesian)

Selamat datang di koleksi dotfiles pribadi saya! Repositori ini berisi file konfigurasi untuk lingkungan pengembangan (development environment) dan kustomisasi sistem saya. Ini adalah proyek yang berjalan (work in progress) dan akan terus saya update seiring berjalannya waktu.

## 🚀 Apa Saja Isinya?

Saat ini, repositori ini mencakup konfigurasi untuk:

- **🐚 Zsh**: Setup shell saya, ditenagai oleh [Oh My Zsh](https://ohmyz.sh/).
- **🖥️ Hyprland**: Konfigurasi tiling window manager (`hyprland.conf`, keybindings, dll).
- **📝 Neovim**: Konfigurasi text editor berbasis [LazyVim](https://www.lazyvim.org/).
- **bar Waybar**: Konfigurasi status bar untuk Wayland.

## 📂 Struktur Folder

```text
/
├── .zshrc           # File konfigurasi Zsh
├── .oh-my-zsh/      # Framework Oh My Zsh dan plugin
├── hyprland/        # Config Hyprland
├── nvim/            # Config Neovim (LazyVim)
└── waybar/          # Config dan style Waybar
```

## 🛠️ Instalasi

> ⚠️ **Catatan:** Selalu backup konfigurasi lama Anda sebelum menggunakan yang baru.

1.  **Clone repositori ini:**
    ```bash
    git clone https://github.com/username-anda/dotfiles.git ~/dotfiles
    ```

2.  **Symlink file:**
    Anda bisa melakukan symlink secara manual atau menggunakan alat seperti GNU Stow.

    *Contoh untuk Zsh:*
    ```bash
    ln -s ~/dotfiles/.zshrc ~/.zshrc
    ```

    *Contoh untuk Neovim:*
    ```bash
    ln -s ~/dotfiles/nvim ~/.config/nvim
    ```

## 🔮 Rencana Kedepan

Saya berencana menambahkan lebih banyak konfigurasi alat lain, seperti:
- Terminal emulator (Kitty/Alacritty)
- Tmux
- Config Git
- Dan lain-lain!

---
*Made with ❤️ by Oath*
