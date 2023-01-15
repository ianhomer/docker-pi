# Docker Pi

Some docker patterns for install on Pi.

## Getting started

    curl -sSL https://get.docker.com | sh
    sudo usermod -aG docker $USER

Then make service directories

    sudo mkdir /services
    sudo chown admin /services
    mkdir -p /services/config/homepage
    mkdir -p /services/config/jellyfin
    mkdir -p /services/data/music

Then

    docker compose -f ./docker-compose-homepage.yaml up -d
    docker compose -f ./docker-compose-jellyfin.yaml up -d

## Troubleshooting


