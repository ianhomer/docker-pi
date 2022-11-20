# Docker Pi

Some docker patterns for install on Pi.

## Getting started

    curl -sSL https://get.docker.com | sh
    sudo usermod -aG docker $USER

Then

    docker compose -f ./docker-compose-pi-hole.yml up -d
    docker compose -f ./docker-compose-gitea.yml up -d
