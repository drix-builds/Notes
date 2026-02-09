tags: [[linux]] [[learning]]
https://docs.docker.com/get-started/docker-overview/

### Installation
##### Ubunto Server
1. Remember to update using: sudo apt update / sudo apt upgrade
2. sudo apt install docker.io

### Manage as non-root user
- add user account to the docker group
	- sudo group add docker
	- sudo usermod -aG docker $USER / drix
	- test with: docker run hello-world
- pull image
	- docker pull ___
- containers will be disposable by default
- let containers access the file system with bind mounts
- docker run -it --name (container name) --volume /home/drix:/mnt

### Compose

- groups of containers that work together managed as a single unit
- containers share a network
- containers have an IP on that created subnet
- YAML specifies names and images for containers

