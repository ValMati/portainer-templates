# Portainer templates

Collection of Portainer templates

| Application | Description |
| ---         | --- |
| [apcupsd](apcupsd/) | apcupsd provides a daemon which will monitor your APC UPS, and shutdown the system when power is no longer being supplied to the UPS. |
| [DIUN](diun/) | Docker Image Update Notifier is a CLI application written in Go to receive notifications when a Docker image is updated on a Docker registry. |
| [Pi-hole + Cloudflared](pihole/) | Pi-hole is a network-level advertisement and Internet tracker blocking application.<br>Cloudflared is a proxy-dns over HTTPS. |

IMPORTANT: The docker-compose.yml files in this repository are designed to run inside Portainer, there are differences between docker-compose and Portainer, so they may not work properly with docker-compose.

DISCLAIMER: The docker-compose files and the rest of the configuration files are the ones I use, they are not intended to be generic or to present all the functionalities of the different containers. Still any suggestions for improvement are welcome. 
