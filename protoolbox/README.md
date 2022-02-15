# Usage
0. Run `docker build -t tikuta/protoolbox:latest .`
0. Link or copy `docker-compose.yml` to your working directory
0. In your working directory, run `docker-compose up`
	* Add `-d` if you want to run in background
	* This will mount current directory `.` to container's `/content`
0. Open `http://127.0.0.1:8080` in your browser
	* Replace `127.0.0.1` to your workstation IP address.
0. Hit Ctrl + C  or run `docker-compose down` to stop the process
