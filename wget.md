# wget


Command wget stands for web get. The wget is a free non-interactive file downloader command. 
Non-interactive means it can work in background when user is not logged in. 
This allows user to get disconnected with the system while wget finish its work.

It can even download entire website as a local version of remote websites, fully recreating the structure of original website. 
In short, you can mirror an entire website with wget.

It supports HTTP, HTTPs and FTP protocol. It is a freely available package and licensed under GNU GPL. 
This command works on all operating systems including MAC Os and Windows.

The main feature of wget is its robustness and recursiveness. 
Due to its robustness, it work even in slow internet connection. 
It automatically starts downloading the file from where it was left in case of network failure. 
Due to its recursiveness, it keeps trying until the file is retrieved completely.

To use wget, you have to give location of the file over HTTP as the wget argument. File will be downloaded in the current directory.

# Installing wget
In some systems wget may not be installed. To install wget use the following command,
````
sudo apt-get install wget
````
# wget Options

# Option	                                                                             Function

````
wget <URL>	                                                                           Download single file
wget -O <fileName> <URL>	                                                             Store with a different file name
wget --limit-rate=<Numberk> <URL>	                                                     Specify download rate/speed
wget -c <URL>	                                                                         Complete the remaining downloaded file
wget -b <URL>	                                                                         Download in background
wget --tries=<Number> <URL>	                                                           Set retrying attempts
wget -i <fileName>	                                                                   Download multiple files
wget --mirror -p --convert-links -P ./local dir <webURL>	                             Download full website
wget --reject=<rejectingFile> <URL>	                                                   Reject a type of file
wget -Q<Value>m -i <fileName>	                                                         Quit downloading on exceeding certain limit
wget -r -A.<fileType> <webURL>	                                                       Download certain file type
wget -o <logFile> <URL>	                                                               Redirect downloading file to the log file
````
