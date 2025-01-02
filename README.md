# My Development Environment Configurations

This repository contains my configuration files for setting up and managing a customized development environment across multiple platforms. It leverages GNU Stow for clean dotfile management, making it easy to apply and maintain configurations for various tools and systems.

## Cross-platform Support
These configurations are tested on macOS and Linux (Arch). Some, like Neovim and Starship, are platform-independent, while some others are tailored for one of the two operating systems.

## Tools and Technologies Configured:
- **Hyprland** & Waybar: Minimalist window manager and status bar configurations --> Linux
- **Neovim**: Customized setup with modular plugins (e.g., LSP, Telescope, Treesitter) --> Linux & Mac
- **Zsh**: Personalized shell configurations with aliases, keymaps, and performance tweaks --> Linux & Mac
- **Starship**: Lightweight, fast, and configurable shell prompt --> Linux
- **WezTerm**: Lua-based terminal emulator customization --> Mac
- **Wallpapers**: My collection of wallpapers.


## How to Use
1. Clone the repository:
```bash
git clone https://github.com/AmiraliSajadi/dev-environment-configs.git
```
2. Navigate to the directory:
```bash
cd ~/dotfiles
```
3. Use GNU Stow to apply a configuration (e.g., Neovim):
```bash
stow nvim
```
This will symlink the nvim configuration files to the appropriate location. Adjust configurations as needed and reload the environment.

