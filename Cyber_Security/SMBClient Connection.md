
> TO connect to an smbclient you will need to use this command 

>smbclient -L  //192.168.1.12 
you will use this parameter to login as anonymous username 

After you list subdirectory if you want to log in inside you will have to add /name of the directory to the previous command l showed you for example smbclient -L //192.168.1.12/backups, l am taking a backup subdirectory as an example you can  try to login in any of them as long it does not have a dollar symbol which mean you will need to have special permission to access.
