# theta-guardian-node-docker-container
Dockerized Theta Guardian Node for Linux (CLI) with custom commands for faster administration

Based on Theta's [Install through Command Line] documentation 

Docker Hub link : https://hub.docker.com/repository/docker/karlpothast/theta-guardian-node

> [Install through Command Line]: https://docs.thetatoken.org/docs/running-a-guardian-node-through-command-line

# Features :
- ### Menu Based Commands ###
- ### Automated Gaurdian Node Installation ###
- ### Built-in snapshot refresh command ###
  - *most common fix for the "Theta is still syncing..." issue*

Run `docker exec` from your server to open a command line within the running container

`docker exec -it <ThetaContainerName> bash`

Once you are within the conainer simply type **theta** to bring up the menu :

`theta`

![alt text][imgMenu]

[imgMenu]: https://github.com/karlpothast/theta-guardian-node-docker-container/blob/master/thetaDockerMenu.png?raw=true "Linux Menu"




