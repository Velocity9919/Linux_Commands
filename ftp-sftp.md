# ftp and sftp

The ftp stands for ````File Transfer Protocol````. It connect to the remote host to exchange files and directories from one host to another over a network which can be LAN or any other.

The sftp stands for Secure ftp.

Most of the ftp commands are applicable to sftp. So wherever, you need to use sftp, you can use it at the place of ftp.
````
ftp prompt
````
The ftp prompt can be used to perform different ftp functions with ftp commands.

# Syntax:
````
ftp
```` 
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/f1384a6f-4064-4e65-9080-17d9d6b0a079)

Linux ftp and sftp1
Look at the above snapshot, by passing ftp command we'll be directed into the ftp prompt. Here, we can write ftp commands to perform different functions.

# ftp help

To open ftp command or help page from ftp prompt , ? Sign or help command is used.

# Syntax:
````
?    
        OR  
help
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/875c2663-3e8c-4955-98df-499cdd95db83)

 
Linux ftp and sftp2
Look at the above snapshot, it displays the help page for the ftp which shows all the ftp commands.

# exiting ftp prompt

To exit from ftp prompt, ! Mark is used. It will take you to the shell prompt.

# Syntax:
````
!
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/54c2972e-00c9-4840-9892-2359405aceae)

Linux ftp and sftp3
Look at the above snapshot, using ! will allow you to exist from the ftp prompt.

# Connect to a ftp site

You can connect to a particular ftp server using either its IP address or the Hostname from the command line.

# Syntax:
````
ftp IP/Hostname  
To connect from ftp prompt,
````  
# Syntax:
````
open IP/Hostname
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/4008d095-f106-4d90-a111-ca4b83f4ccf7)

Linux ftp and sftp4
# Downloading file using
To download a file from a remote server, use get command.

# Syntax:
````
get fileName  
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/9328ce27-38ac-41a2-8284-c52d74ed5143)

Linux ftp and sftp5
To download files, user has to be in correct mode, either binary or ascii mode. In ascii mode, text files can be transferred while in binary mode, all other type of files can be transferred.

# Saving downloaded file with another name
If you want to save a downloaded file with another name, following command can be used.

# Syntax:
````
get fileName newName  
````
Example:

get pro2356.php project.php
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/0bce90b1-bb1d-438f-b0fa-791c1b64cc4e)

Look at the above snapshot, we are downloading a file named as pro2356.php want to save it as ```` project.php````

# Changing ftp mode
There are two modes, one is binary (for all other files) and other is ascii (for text files) mode.
````
To ascii mode
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/031abce4-83a1-4e0e-8d1e-6c074ed187cf)

To binary mode

![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/ceca417e-1f07-4f16-9b69-071d07ee5c68)

# Uploading file using
To download a file from a remote server, use put command.

# Syntax:
````
put fileName
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/c91f647f-f7dd-4b8b-8a7e-90913bae684e)

Listing files in current folder

You can view a remote directory using ls command.

![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/ae6f2717-a26d-4f7f-92ad-046420752506)

Downloading multiple files using

The ````mget```` command is used to fetch multiple files from ftp server.

# Syntax:
````
mget *.txt
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/a88e512e-38aa-4c95-97e6-e7a35ca31100)

Uploading multiple files using

The ```` mput ````command is used to upload multiple files from ftp server.

# Syntax:
````
mput *.txt
```` 
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/e5b1501b-a3d7-4864-b281-7e33e821b57a)

# close command
When you want to connect to another server without existing the ftp prompt, ````close```` command should be used. Then you can connect to a new server from ftp prompt.

# Syntax:
````
close
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/a1b3a56d-a58a-4602-8eab-53a1540f5886)

