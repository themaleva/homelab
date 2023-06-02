# Homelab
Documentation &amp; configuration for maintaining and managing my homelab

## Steps to recreate a working environment with Docker!
1. Clean OS install with SSH access.
2. Mount a data drive on /data/docker
3. Mount additional data drive on /data/entertainment (if required for Plex/Jellyfin)
4. On new node, run `ssh-keygen` and add the .pub contents to GitHub to clone this repo.
5. Install Docker - https://docs.docker.com/engine/install/ubuntu/

## Now we have docker you can start to create the containers


## Connecting to your network remotely

I use TailScale.com to connect my network together. It creates a mesh VPN between all your devices and it's free for up to 100 devices, which means by installing it on your server(s), phones, etc. you can simply connect and then visit the TailScale IP provided in the UI.ad