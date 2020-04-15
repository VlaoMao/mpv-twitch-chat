# mpv-twitch-chat

Displays Twitch.tv chat replay when watching VoDs with mpv.

# Installation

- Install `mpv` and `lua`
- Install `luarocks-5.2` (or 5.1 if your `mpv` uses that instead) with your package manager of choice
	- OS X: `brew install lua`
	- Arch Linux: `pacman -S luarocks5.2`
- Run `install.sh`

# Preparation

- Download twitch video to file (example: video.mp4)
- Download rechat file in json format (via tcd: tcd --format json --video xxxxx) and name it according to video filename (video.rechat.json)
- run mpv
