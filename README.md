# Traefik Docker
Example of how Traefik can be used as a reverse proxy in combination with Docker. 

## Requirements
- Docker
- Docker Compose

## Usage
- Clone this repository
- Run `docker compose up -d`
- Open http://localhost:8080 in your browser to access the Traefik dashboard

## Services
- Open http://nodejs.localhost in your browser for NodeJS
- Open http://example.localhost in your browser for NginX 
- Open http://example2.localhost or http://example2.localhost in your browser for another NginX webserver
- Open http://whoami.localhost in your browser for whoami
- Open http://example.localhost/whoami2 in your browser for whoami2