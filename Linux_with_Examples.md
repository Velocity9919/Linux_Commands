# Linux Directory Commands

# 1. pwd Command

The pwd command is used to display the location of the current working directory.


# Syntax:
````
pwd
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/69406407-22d0-4287-85f7-9f523c809320)

# 2. mkdir Command

The mkdir command is used to create a new directory under any directory.

# Syntax:
````
mkdir <directory name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/2d95e641-2e02-4d5b-a5ad-3b3725dfd23f)

# 3. rmdir Command

The rmdir command is used to delete a directory.

# Syntax:
````
rmdir <directory name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/da5c1873-a38c-4b7f-95ff-fb503eb76ffb)


# 4. ls Command

The ls command is used to display a list of content of a directory.

# Syntax:
````
ls
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/1e2ac0fe-3ee7-46cd-81ad-7d40877d2409)

# 5. cd Command

The cd command is used to change the current directory.

# Syntax:
````
cd <directory name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/af4d4da1-a457-4feb-a85c-0378e3f733d2)

# Linux File commands

# 6. touch Command

The touch command is used to create empty files. We can create multiple empty files by executing it once.

# Syntax:
````
touch <file name>  
touch <file1>  <file2> ....
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/7e200ab4-384f-403d-89dc-f55eb9367b40)

# 7. cat Command

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

# Syntax:
````
cat [OPTION]... [FILE]..
````
To create a file, execute it as follows:
````
cat > <file name>  
// Enter file content
```` 
Press "CTRL+ D" keys to save the file. To display the content of the file, execute it as follows:
````
cat <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/a8b3a5b0-8c0d-469a-a943-5dfd6ec5f041)

# 8. rm Command

The rm command is used to remove a file.

# Syntax:
````
rm <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/bbafd385-6ec4-4cc6-b4a0-98f20357929e)

# 9. cp Command

The cp command is used to copy a file or directory.

# Syntax:

To copy in the same directory:
````
cp <existing file name> <new file name>
```` 
To copy in a different directory:
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/85689aff-44e1-4c31-aca6-df0caf95b0f4)

# 10. mv Command

The mv command is used to move a file or a directory form one location to another location.

# Syntax:
````
mv <file name> <directory path>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/810f2bc8-63f0-4d43-875e-f0ef21bd6a17)

# 11. rename Command

The rename command is used to rename files. It is useful for renaming a large group of files.

# Syntax:
````
rename 's/old-name/new-name/' files  
````
For example, to convert all the text files into pdf files, execute the below command:
````
rename 's/\.txt$/\.pdf/' *.txt
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/90599820-cfb9-4782-8c77-350f4538a8a8)

# Linux File Content Commands
# 12. head Command

The head command is used to display the content of a file. It displays the first 10 lines of a file.

# Syntax:
````
head <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/4cc77e20-5dea-4bcf-8901-1b85bbe48f70)

# 13. tail Command

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

# Syntax:
````
tail <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/232504dc-f563-4d9b-9623-c3a1b92d5b92)

# 14. tac Command

The tac command is the reverse of cat command, as its name specified. It displays the file content in reverse order (from the last line).

# Syntax:
````
tac <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/2a2fa88b-d71b-4b14-aaee-68cccc25c319)

# 15. more command

The more command is quite similar to the cat command, as it is used to display the file content in the same way that the cat command does. The only difference between both commands is that, in case of larger files, the more command displays screenful output at a time.

In more command, the following keys are used to scroll the page:

````ENTER key:```` To scroll down page by line.

````Space bar:```` To move to the next page.

````b key:```` To move to the previous page.

````/ key:```` To search the string.

# Syntax:
````
more <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/d4acd968-2254-4015-8062-b4b58382fa71)

# 16. less Command

The less command is similar to the more command. It also includes some extra features such as 'adjustment in width and height of the terminal.' Comparatively, the more command cuts the output in the width of the terminal.

# Syntax:
````
less <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/db211454-e90f-4b6c-8827-ba562ada99cc)


# Linux User Commands
# 17. su Command

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

# Syntax:
````
su <user name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/088bc660-b509-4859-8d3e-56ccefcb4fa7)

# 18. id Command

The id command is used to display the user ID (UID) and group ID (GID).

# Syntax:
````
id
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/e9205a92-4ed7-4ebe-88da-013552f0b00a)

# 19. useradd Command

The useradd command is used to add or remove a user on a Linux server.

# Syntax:
````
useradd  username
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/863cb9c0-ae4f-402b-baa8-081a90bf2573)

# 20. passwd Command

The passwd command is used to create and change the password for a user.

# Syntax:
````
passwd <username>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/2fa43260-c754-4ede-82bf-13554c803a70)

# 21. groupadd Command

The groupadd command is used to create a user group.

# Syntax:
````
groupadd <group name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/87389518-d788-4402-938e-66477b653ebc)

# Linux Filter Commands
# 22. cat Command

The cat command is also used as a filter. To filter a file, it is used inside pipes.

# Syntax:
````
cat <fileName> | cat or tac | cat or tac |. . .
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/6bb86709-1ee1-4b3c-98ee-9eed503e5e07)

# 23. cut Command

The cut command is used to select a specific column of a file. The '-d' option is used as a delimiter, and it can be a space (' '), a slash (/), a hyphen (-), or anything else. And, the '-f' option is used to specify a column number.

# Syntax:
````
cut -d(delimiter) -f(columnNumber) <fileName>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/18a1003a-b542-484b-bfb3-4a3bdbf567ed)

# 24. grep Command

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

# Syntax:
````
command | grep <searchWord>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/9e5c9a62-c4d6-417f-ae4c-7c79e7440e9d)

# 25. comm Command

The 'comm' command is used to compare two files or streams. By default, it displays three columns, first displays non-matching items of the first file, second indicates the non-matching item of the second file, and the third column displays the matching items of both files.

# Syntax:
````
comm <file1> <file2>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/4532c112-4796-4a18-8c27-ad9820a58165)

# 26. sed command

The sed command is also known as stream editor. It is used to edit files using a regular expression. It does not permanently edit files; instead, the edited content remains only on display. It does not affect the actual file.

# Syntax:
````
command | sed 's/<oldWord>/<newWord>/'
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/bffcadc2-3114-47e9-a567-4a5aede4ee68)

# 27. tee command

The tee command is quite similar to the cat command. The only difference between both filters is that it puts standard input on standard output and also write them into a file.

# Syntax:
````
cat <fileName> | tee <newFile> |  cat or tac |.....
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/854c6f14-4f0b-4d39-9384-b62c6dafbcb9)

# 28. tr Command

The tr command is used to translate the file content like from lower case to upper case.

# Syntax:
````
command | tr <'old'> <'new'>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/7edcf978-53c2-4eda-8c29-18622de92ec8)

# 29. uniq Command

The uniq command is used to form a sorted list in which every word will occur only once.

# Syntax:
````
command <fileName> | uniq
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/81fcf335-9ef8-43be-8bd7-be5b2ec2ba0e)

# 30. wc Command

The wc command is used to count the lines, words, and characters in a file.

# Syntax:
````
wc <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/a0d1fa05-06ea-4edc-8e41-4c94b9c3a05b)

# 31. od Command

The od command is used to display the content of a file in different s, such as hexadecimal, octal, and ASCII characters.

# Syntax:
````
od -b <fileName>      // Octal format  
od -t x1 <fileName>   // Hexa decimal format  
od -c <fileName>     // ASCII character format
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/31e185a1-954b-44e1-bcc1-e9538d229f42)

# 32. sort Command

The sort command is used to sort files in alphabetical order.

# Syntax:
````
sort <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/295d7028-b98b-4388-90ec-191337d1ced9)

# 33. gzip Command

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

# Syntax:
````
gzip <file1> <file2> <file3>...
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/b71b4b49-0752-4fbf-9b84-8008cd249120)

# 34. gunzip Command

The gunzip command is used to decompress a file. It is a reverse operation of gzip command.

# Syntax:
````
gunzip <file1> <file2> <file3>. .
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/a522601a-5e3b-4820-a228-6f85862de12a)

# Linux Utility Commands

# 35. find Command

The find command is used to find a particular file within a directory. It also supports various options to find a file such as byname, by type, by date, and more.

The following symbols are used after the find command:

(.) : For current directory name

(/) : For root

# Syntax:
````
find . -name "*.pdf"
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/fd1f95d8-b574-4ff9-9b6f-b53487a114b6)

# 36. locate Command

The locate command is used to search a file by file name. It is quite similar to find command; the difference is that it is a background process. It searches the file in the database, whereas the find command searches in the file system. It is faster than the find command. To find the file with the locates command, keep your database updated.

# Syntax:
````
locate <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/f25d9a98-0e91-4b6c-92bc-704483c28441)

# 37. date Command

The date command is used to display date, time, time zone, and more.

# Syntax:
````
date
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/d83934cd-b2a2-4c00-99ee-76c49009c256)

# 38. cal Command

The cal command is used to display the current month's calendar with the current date highlighted.

# Syntax:
````
cal<
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/c086772e-b7bc-4e14-bc58-0a3f39183700)

# 39. sleep Command

The sleep command is used to hold the terminal by the specified amount of time. By default, it takes time in seconds.

# Syntax:
````
sleep <time>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/2c825c83-4bc1-49ac-8e42-088bedc11cab)

# 40. time Command

The time command is used to display the time to execute a command.

# Syntax:
````
time
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/d2b7dfa1-a6f9-4459-a3b1-a21df8e44a7d)

# 41. zcat Command

The zcat command is used to display the compressed files.

# Syntax:
````
zcat <file name>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/e4f40a12-cbe3-4fc9-a6b4-8102477ce9e8)

# 42. df Command

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

# Syntax:
````
df
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/9f19a0b6-d83a-46c1-b7b4-3ec98258beba)

# 43. mount Command

The mount command is used to connect an external device file system to the system's file system.

# Syntax:
````
mount -t type <device> <directory>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/93a4ba17-327a-416d-a2e5-cda63bc46e56)

# 44. exit Command

Linux exit command is used to exit from the current shell. It takes a parameter as a number and exits the shell with a return of status number.

# Syntax:
````
exit
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/0ad9a8af-a704-4afe-80fa-a515927caa21)

After pressing the ENTER key, it will exit the terminal.

# 45. clear Command

Linux clear command is used to clear the terminal screen.

# Syntax:
````
clear
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/13282e62-1c18-40f9-9017-dbbdea63667f)

After pressing the ENTER key, it will clear the terminal screen.

# Linux Networking Commands

# 46. ip Command

Linux ip command is an updated version of the ipconfig command. It is used to assign an IP address, initialize an interface, disable an interface.

# Syntax:
````
ip a or ip addr
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/12c82c01-337d-4387-a767-1a7757bdd3a1)

# 47. ssh Command

Linux ssh command is used to create a remote connection through the ssh protocol.

# Syntax:
````
ssh user_name@host(IP/Domain_name)</p>  
````
# 48. mail Command

The mail command is used to send emails from the command line.

# Syntax:
````
mail -s "Subject" <recipient address>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/30747d72-a965-4ea4-b50c-0766e3c53fa4)

# 49. ping Command

The ping command is used to check the connectivity between two nodes, that is whether the server is connected. It is a short form of "Packet Internet Groper."

# Syntax:
````
ping <destination>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/24df8b67-fc42-42da-89b9-0b8088448984)

# 50. host Command

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

# Syntax:
````
host <domain name> or <ip address>
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/8e6f8ce3-f3a9-48c5-a526-0be723d6ba65)


