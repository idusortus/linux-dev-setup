# Linux Dev Setup

My Pop!_OS development environment configs and snapshots.

## Structure
- `snapshots/` — JSON snapshots of installed tools and versions
- `configs/` — terminal and shell config files

## Restore configs
```bash
cp configs/zshrc ~/.zshrc
cp configs/kitty.conf ~/.config/kitty/kitty.conf
cp configs/startup.conf ~/.config/kitty/startup.conf
cp configs/starship.toml ~/.config/starship.toml
cp configs/update-dev-tools ~/.local/bin/update-dev-tools
chmod +x ~/.local/bin/update-dev-tools
source ~/.zshrc
```
