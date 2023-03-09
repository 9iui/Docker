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