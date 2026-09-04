# README

## current versions
### mediarr
|image|source|version|pulled|
|-----|------|-------|------|
|gluetun|`qmcgaw/gluetun`|3.41.3|08/07/2026 07:48:38|
|qbittorrent|`lscr.io/linuxserver/qbittorrent`|5.2.3|08/10/2026 17:26:06|
|bypar|`ghcr.io/thephaseless/bypar`|*latest*|08/11/2026 06:06:11|
|prowlarr|`lscr.io/linuxserver/prowlarr`|2.5.2.5491|08/05/2026 02:14:51|
|readarr|`lscr.io/linuxserver/radarr`|6.3.0.10514|08/02/2026 13:51:32|
|sonarr|`lscr.io/linuxserver/sonarr`|4.0.19.2979|08/07/2026 19:57:23|
|recyclarr|`ghcr.io/recyclarr/recyclarr`|8|08/06/2026 22:14:00|
|bazarr|`lscr.io/linuxserver/bazarr`|1.6.0|08/11/2026 18:11:11|
|seerr|`ghcr.io/hotio/seerr`|3.4.1|07/30/2026 07:14:03|

### audiobookshelf
|image|source|version|pulled|
|-----|------|-------|------|
|audiobookshelf|`ghcr.io/advplyr/audiobookshelf`|latest|07/27/2026 18:34:22|

## ideas/projects/containers
### new `scrypted` project

- video camera integrarion
- full, historic recording
- facial recognition?
- stream to Google Home

### new `nginx` reverse proxy project

- new proxy network needed
- keep internal (for now) at *.local adresses
- (future) owned domain
  - Let's Encrypt certs
  - external access?

### new `homarr` / `homepage` project

- container and service monitoring?
  - move to separate container

### new `networks` project

- (networks) create a new project for networks
  - bridge network and glutun - pull out gluetun from mediarr
