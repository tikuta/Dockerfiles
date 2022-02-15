# Prerequirements
* Docker version 20.10.7, build 20.10.7-0ubuntu5~20.04.2
	* In most case, nvidia-docker is suitable to use GPUs.
	* Rootless docker is preferred to inherit host file permissions.
* docker-compose version 1.29.2, build 5becea4c

# Basic Usage
See README in each directory for detail.

0. Build containers
0. Run `docker-compose up`
	* Add `-d` if you want to run in background
0. Hit Ctrl + C  or run `docker-compose down` to stop the process
