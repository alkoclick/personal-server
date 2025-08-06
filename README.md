# Personal-server

My home automation setup, currently on a Raspberry Pi 4B.

## Required for setup

* Docker
* Git

## Current services to be ported to code

* Syncthing (for jellyfin)

## Current services (ported to code)

* [Jellyfin](https://github.com/jellyfin/jellyfin)
* [Tailscale](https://tailscale.com/)
* [qBittorrent](https://github.com/qbittorrent/qBittorrent)
* [Filebrowser](https://filebrowser.org/)
* [Glances](https://glances.readthedocs.io/en/latest/index.html)
* [It-tools](https://github.com/CorentinTh/it-tools)
* [Grist](https://github.com/gristlabs/grist-core)

## TODO
* Actually store torrents in a volume
* Better backups for jellyfin config (esp playlists)

#### Jellyfin upgrades
* yt-dlp + Jellyfin integration? E.g: https://github.com/jmbannon/ytdl-sub?tab=readme-ov-file
