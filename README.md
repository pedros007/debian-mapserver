Debian Jessie image with Mapserver installed.  Built on top of [https://github.com/pedros007/debian-gdal](debian-gdal).  Supervisor runs Nginx as a reverse proxy to Mapserver running on a unix socket as a FastCGI program.

This Docker Image is available on Dockerhub at [debian-mapserver](https://hub.docker.com/r/pedros007/debian-mapserver)

# Usage

See [mapserver-docker](https://github.com/pedros007/mapserver-docker)
for some usage instructions.  Eventually I'll update the run
instructions in the README for this repo

# Build

	docker build -t pedros007/debian-mapserver:7.0.4 .
