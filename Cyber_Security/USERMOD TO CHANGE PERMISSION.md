
### In order to give sudo permission to a new user you will need to use this command ![[Pasted image 20240208164008.png]]
As you can see you use the -aG parameter to describe the group that you want to include the user follow by the user name and the group is sudo group which is the same as root.

### How to delete a user from a group 

- In order to delete a user from a group you will need to use the following command 

![[Pasted image 20240208164229.png]]

### Lock and unlocking account in linux 

- To lock the account use this command 

![[Pasted image 20240208164345.png]]

- To unlock the account use this command 

![[Pasted image 20240208164450.png]]

- Set expiration dat to an account 

![[Pasted image 20240208164548.png]]

- Add user to a group 

![[Pasted image 20240209131150.png]]

- Remove user from a group

![[Pasted image 20240209131251.png]]
###### gpasswd is used for group you can use the parameter -a to add a member to a group and -d to remove it and also to add password to a group by running this command ==sudo gpasswd name of the group== that you want to create a password for

- Add user to a group using gpasswd 
 
![[Pasted image 20240209131910.png]]

- Remove user from a group 

![[Pasted image 20240209132013.png]]


### groups command will show you all the group that your user is part of

- TO see all the groups in your system you can use 2 command which are ==getent group== and ==cat /etc/group==

