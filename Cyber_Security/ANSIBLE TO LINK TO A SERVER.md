# link to a  Ubuntu server or any other Debian distro

- ansible all --key-file ~/.ssh/ansible_only -i inventory -m ping

	As you can see the first ansible name is to call the ansible program, ansible_only is the ssh Private key name, the ==-i== is for the inventory file and ==-m== is the for the module which l am using here is ping
# Create an ansible inventory file 
- To create an ansible inventory file use nano and type inside the ip of the server you want to manage and if is giving dns problem use the username of the server follow by the ip for example peter@10.0.0.223 close and save the file 

# Create a crf file and add the inventory file to it

- use nano and inside type the next 


![[Screenshot from 2024-08-21 21-26-36.png]]
As you can see the predifined variable inventory is to add the name of our inventory and the private_key_file  is to add our ssh private this way we do not need to use the long command in the top to ping and go to be able to use the command below 

# Connet and ping to the server with asinble
-  ==ansible all -m ping== this way it will look 
  