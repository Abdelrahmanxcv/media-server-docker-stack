# Media Server Docker Stack

This is a ready-to-deploy Docker setup for:

- Plex
- Sonarr
- Radarr
- Overseerr
- qBittorrent
- SABnzbd
- Tautulli
- NGINX Proxy Manager

## Usage

Clone this repo:

git clone https://github.com/Abdelrahmanxcv/media-server-docker-stack

Copy .env file:

cp .env.example .env

Edit it:

nano .env

Deploy:

docker-compose up -d
