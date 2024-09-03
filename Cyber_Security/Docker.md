
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


## How to create a  docker file 
In order to create a docker file you will need to go to a  text
editor and create a file and inside you will type the next command 
![[Screenshot from 2024-09-02 21-20-32.png]]
As you can see the FROM is to specify the name of the images that you want this scrip to run 

Hint: if you know bash you will know that the commands on the images does, for example the RUN apt update && upgrade -y update and upgrade the system and the COPY as it name mentions copy a file to a directory in the container 

### How to create a container with the file specification above

- sudo docker build --tag any_name . 
The dot at the end that this will run with all the file in the current directory which is the docker-file that we create above.

Afte that you just need to run the docker images command to see the new images and then to run it you just need to use the previous command that we always use to start a container 

- sudo ==docker run -it name_of_the_container==
