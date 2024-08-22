# Create an ssh-key




- ssh-keygen -t ed25519 -C "name of ssh"

# Copy my ssh key to a server 

- ssh-copy-id username@server_ip after this the key will be copy in the ~/.ssh/authorized_keys file.

# Copy ssh key to our server

- ==ssh-copy-id -i ~/.ssh/id_ed25519.pub name of the machine@ ip of the server you want to copy the key to ==
	- After you also want to use the next command which allow you to enter the passphrase only once ==eval $(ssh-agent)== which which will list the PID of the process
		- To add the phrase use the next command ==ssh-add== this will add the  passphrase that you will only need to use it once and it will log in in ssh without having to enter the phrase over and over again. 