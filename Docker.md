### Installation
##### Ubunto Server
1. Remember to update using: sudo apt update
2. sudo apt install docker.io

### Manage as non-root user
- add user account to the docker group
	- sudo group add docker
	- sudo usermod -aG docker $USER / drix
	- test with: docker run hello-world
- pull image
	- docker pull ___
- containers will be disposable by default
- 