clear

# How to do an STTY treatment in a kali 

First step is to use the 
- script /dev/null -c bash (this will give you a command promp)
- click control + z (this will kick you out of the machine which is okey)
- stty raw -echo; fg
- Type reset
- xterm 
- export TERM=xterm
- export SHELL=bash