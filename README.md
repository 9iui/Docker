# Docker
my personal file on learning and creating docker images and files...

## container architecture  

- docker containers  -- library ,application 
- docker engine - is almost like the hypervisor , it is lighter than the hypervisor , all containers running on the host runs the same operation system . 
- container runs on a container host  via the docker engine 
- containers only contains the  app,lib and runtime env 
-  no operating system (it uses the container host  OS )
- they are super light weight
- they can be impacted by other containers (noisy neighbours)-other containers can be impacted 
- they are not fully isolated  from each other 
- they where created to fix an application shipping problem 
- host the application and other lib needed for it to run 

## Docker commands 

*docker run [IMAGE] -d*: This command runs a container based on a Docker image. the d is to detach form your terminal 

*docker ps*: This command lists all the running containers.

*docker stop [CONTAINER]*: This command stops a running container.

*docker rm [CONTAINER]*: This command removes a container.

*docker images*: This command lists all the Docker images on your system.

*docker rmi [IMAGE]*: This command removes a Docker image.

*docker pull [IMAGE]*: This command downloads a Docker image from a registry.

*docker push [IMAGE]*: This command uploads a Docker image to a registry.

*docker build [DIRECTORY]*: This command builds a Docker image from a Dockerfile in a specified directory.

*docker exec [CONTAINER] [COMMAND]*: This command executes a command in a running container.

*docker logs [CONTAINER]*: This command displays the logs of a container.

*docker network ls*: This command lists all the Docker networks on your system.

*docker network create [NETWORK]*: This command creates a Docker network.

*docker network connect [NETWORK] [CONTAINER]*: This command connects a container to a network.

*docker network disconnect [NETWORK] [CONTAINER]*: This command disconnects a container from a network.