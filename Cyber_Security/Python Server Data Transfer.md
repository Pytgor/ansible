
### In order to transfer a file using linux you will have to use those commands. 

>In the machine that you have the file that you want to transfer you will have to run this command in the same directory that you have the file to transfer

![[Pasted image 20231024205423.png]]

>In the machine that you want to send the file to you will have to run this command using the ip address of the machine owner of the file and the port where the server is running which is the port 80 in this case 

![[Pasted image 20231024205516.png]]
### REMEMBER TO USE THE PORT NUMBER OF THE CONNECTION AFTER THE IP TARGET SEPARATING THEN WITH A COLOMN :

#### for example
wget http://12.168.0.1:80/name.txt