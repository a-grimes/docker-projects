# README

## mediarr

### to-do

- (mediarr) stop project/containers and move container folders to `mediarr/config`
  - update `compose.yaml` and point to new config locations
- (gluetun) update `VPN_PORT_FORWARDING_UP_COMMAND` and `VPN_PORT_FORWARDING_DOWN_COMMAND` commands with appropriate IP address
- (gluetun) update healthcheck to avoid errors
- (bazarr) complete setup
- (radarr/sonarr) setup appropriate quality profiles (1080p and UHD only?)
  - restrict to average file per expected download size 720p/1080p and UHD

## ideas/projects/containers

### new `audiobookshelf` container

- add to `mediarr`?

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
