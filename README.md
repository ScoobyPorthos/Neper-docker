# Neper-Docker

## Neper, What is it ? 
>Neper is a software package for polycrystal generation and meshing. It can deal with 2D and 3D polycrystals with very large numbers of grains. 
To know more about it, go and check : 
* http://neper.sourceforge.net/
* https://github.com/rquey/neper

## Neper-Docker, What is it ? 
* Docker ? 
>Docker is a software technology providing containers, promoted by the company Docker, Inc. Docker provides an additional layer of abstraction and automation of operating-system-level virtualization on Windows and Linux.

* Neper-Docker is therefore a ubuntu docker container with Neper 3.1.0 installed in it. So we will just have to pull the neper-docker repository from docker-cloud and run it ! 

## Installation / SettingUP

0. Install Docker (https://www.docker.com/)
1. pull the docker repository `docker pull scoobyporthos/neper-docker`
2. Run it ! 
	* With the `docker-compose` - clone the docker-compose.yml form this repository
	* `docker run -it --name neper -v neper:/home/Neper/ -w /home/Neper/exec scoobyporthos/neper-docker`

