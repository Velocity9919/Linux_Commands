ftp and sftp
The ftp stands for File Transfer Protocol. It connect to the remote host to exchange files and directories from one host to another over a network which can be LAN or any other.

The sftp stands for Secure ftp.

Most of the ftp commands are applicable to sftp. So wherever, you need to use sftp, you can use it at the place of ftp.

ftp prompt
The ftp prompt can be used to perform different ftp functions with ftp commands.

Syntax:

ftp  
Linux ftp and sftp1
Look at the above snapshot, by passing ftp command we'll be directed into the ftp prompt. Here, we can write ftp commands to perform different functions.

ftp help
To open ftp command or help page from ftp prompt , ? Sign or help command is used.

Syntax:

?    
        OR  
help  
Linux ftp and sftp2
Look at the above snapshot, it displays the help page for the ftp which shows all the ftp commands.

exiting ftp prompt
To exit from ftp prompt, ! Mark is used. It will take you to the shell prompt.
ADVERTISEMENT


Syntax:

!  
Linux ftp and sftp3
Look at the above snapshot, using ! will allow you to exist from the ftp prompt.

Connect to a ftp site
You can connect to a particular ftp server using either its IP address or the Hostname from the command line.

Syntax:

ftp IP/Hostname  
  
To connect from ftp prompt,  
Syntax:

open IP/Hostname  
Linux ftp and sftp4
Downloading file using
To download a file from a remote server, use get command.

Syntax:

get fileName  
Linux ftp and sftp5
To download files, user has to be in correct mode, either binary or ascii mode. In ascii mode, text files can be transferred while in binary mode, all other type of files can be transferred.

Saving downloaded file with another name
If you want to save a downloaded file with another name, following command can be used.

Syntax:

get fileName newName  
Example:

get pro2356.php project.php

Linux ftp and sftp6
ADVERTISEMENT

ADVERTISEMENT

Look at the above snapshot, we are downloading a file named as pro2356.php want to save it as project.php

Changing ftp mode
There are two modes, one is binary (for all other files) and other is ascii (for text files) mode.

To ascii mode

Linux ftp and sftp7
To binary mode

Linux ftp and sftp8
Uploading file using
To download a file from a remote server, use put command.

Syntax:

put fileName  
Linux ftp and sftp9
Listing files in current folder
You can view a remote directory using ls command.

Linux ftp and sftp10
Downloading multiple files using
The mget command is used to fetch multiple files from ftp server.

Syntax:

mget *.txt  
Linux ftp and sftp11
Uploading multiple files using
The mput command is used to upload multiple files from ftp server.

Syntax:

mput *.txt  
Linux ftp and sftp12
close command
When you want to connect to another server without existing the ftp prompt, close command should be used. Then you can connect to a new server from ftp prompt.

Syntax:

close  
Linux ftp and sftp13
