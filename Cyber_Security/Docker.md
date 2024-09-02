
# How to use docker 
The first command that you want to use is 
- docker images : This command will show all the images in the container, after this you will go to a website called [Docker Hub Container Image Library | App Containerization](https://hub.docker.com/)
- docker run ubuntu : As you can see ubuntu is the name of the container 
  In order to run the image you will run the next command
  - docker run -it ubuntu : which is the name of the container to run


## How to delete a docker image

In order to delete a docker image you will need to use the next command 
- docker rmi ubuntu : where ubuntu is the name of the container that l want to remove.


## How to delete a Docker container

- docker rm container_id
## Log back after you exit docker 

In order to log in back after deleting the docker image you will need to run the next commands
- docker ps -a to see the process 
- docker start container_id :  of  the machine to start the docker images again
- To log in  after doing the previous command use the next command exec -it 39f bash : where 39f is are the first character of the container id where you do not need to type everything because docker know what you are referring to.