# DIUN

[DIUN](https://github.com/crazy-max/diun) is a software to detect new versions of docker images and notify it by differente ways. The *docker-compose.yml* is configured to search for new versions of running containers and the images specified in the *custom-images.yml* file. In the case of detecting a new version, DIUN notifies it via Telegram. Additionally DIUN notifies each execution to the service [https://healthchecks.io/](https://healthchecks.io/).
