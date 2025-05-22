# Docker Commands
## To Insatll
  ```
    sudo apt-get install docker.io
  ```
it will install
  1 docker enjine (docker service)
  2 docker demon (docker d)
  3 docker contaierd
  4 docker CLI

##To Check the Docker running status
  ```
  sudo systemctl status docker
```
it will display the status of docker

## when you Run below Command 
  the it will display a mass Permision dinied
  To give permisin you have to add user in Docker Group

  ```
  sudo usermod -aG docker $USER
```
this commond will add the currnet user in Docker Gorup

  ## To check Dockers Process:
   ```
    docker ps
  ```
it display the Running Container

## To Chech Images which Are avaleb in yousystem
```
docker images
```
it will show you the numver of images are avlable in Your System

## now you cnn login in docker Hub 
```
docker login
```
it will ask you for User name and Password
fill the Detalis and login

## to Chech the installation is proper or no
```
docker run hello-world
```
it will dispay an hello massage

## To make Docker image
go to in Project where Dockerfile is avlable
```
docker build -t example-image .
```
the above cmd will make image whith name example-app

## to make contaimer from Image 
```
docker run example-app
```
it will make container and execute that

