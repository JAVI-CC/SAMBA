# SAMBA
Docker imagen SAMBA para compartir un directorio entre diferentes sistemas.

# USAGE 
docker run --name SAMBA -v /home/SAMBA-HOST:/SAMBA -p 139:139 -p 445:445 -id javi98/samba

# USER AND PASSWORD
USER: USUARIO 

PASSWORD: 12345678

# Problem i do not have permission to create files
chmod 777 /home/SAMBA-HOST
