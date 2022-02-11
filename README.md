# Prerequirements
* Docker version 20.10.12, build e91ed57
* docker-compose version 1.29.2, build 5becea4c

# Usage
0. Run `docker build -t tikuta/protoolbox:latest protoolbox`
0. Run `docker-compose up`
	* Add `-d` if you want to run in background
	* This will mount current directory `.` to container's `/content`
0. Open `http://127.0.0.1:8080` in your browser
0. Hit Ctrl + C  or run `docker-compose down` to stop the process
