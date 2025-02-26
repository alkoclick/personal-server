# Personal-server

My home automation setup, currently on a Raspberry Pi 4B.

## Required for setup

* Docker
* Git

## Current services to be ported to code

* Jellyfin
* Syncthing (for jellyfin)

## Current services (ported to code)

* [Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)
* [Dashy](https://github.com/Lissy93/dashy)
* [Syncthing](https://github.com/syncthing/syncthing)

## TODO

#### General
* Move the paperless docker-compose to the top level

#### Monitoring
* Set up S.M.A.R.T. monitoring
* Some kind of uptime monitoring

#### Jellyfin upgrades
* Multiple users
* Upload music via the UI?
* Expose via Tailscale
* Consider hardware acceleration
* yt-dlp + Jellyfin integration?
* Add music library syncing on Syncthing