# Bashthemes – Starship Setup

## Installation

1. Starship installieren
curl -sS https://starship.rs/install.sh | sh

2. Nerd Font installieren
wget https://github.com/ryanoasis/nerd-fonts/releases/latest/download/JetBrainsMono.zip
unzip JetBrainsMono.zip -d ~/.fonts
fc-cache -fv
→ Terminal-Schriftart auf "JetBrainsMono Nerd Font" setzen

3. Config übernehmen
mkdir -p ~/.config
cp starship.toml ~/.config/starship.toml

4. Starship in Bash aktivieren
echo 'eval "$(starship init bash)"' >> ~/.bashrc
source ~/.bashrc
