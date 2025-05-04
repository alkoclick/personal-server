# Personal-server

My home automation setup, currently on a Raspberry Pi 4B.

## Required for setup

* Docker
* Git

## Current services to be ported to code

* Syncthing (for jellyfin)

## Current services (ported to code)

* [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)
* [Dashy](https://github.com/Lissy93/dashy)
* [Syncthing](https://github.com/syncthing/syncthing)
* [Jellyfin](https://github.com/jellyfin/jellyfin)
* [Tailscale](https://tailscale.com/)
* [qBittorrent](https://github.com/qbittorrent/qBittorrent)
* [Filebrowser](https://filebrowser.org/)
* [Glances](https://glances.readthedocs.io/en/latest/index.html)
* [It-tools](https://github.com/CorentinTh/it-tools)
* [Grist](https://github.com/gristlabs/grist-core)

## TODO
* Some kind of uptime monitoring
* Add music library syncing on Syncthing
* Some kind of gitops to automatically fetch and deploy changes to the server
* Remote tailscale SSH access
* Translation tooling:
  * Supports on-the-spot translations
  * Supports document translation
  * (Optional) Supports voice translation

## Backlog
* Make a fork of dashy with less resource usage

#### Monitoring
* Set up S.M.A.R.T. monitoring

#### Jellyfin upgrades
* yt-dlp + Jellyfin integration? E.g: https://github.com/jmbannon/ytdl-sub?tab=readme-ov-file
