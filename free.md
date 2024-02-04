# free command

The free command gives information about used and unused memory usage and swap memory of a system. By default, it displays memory in kb (kilobytes).

Memory mainly consists of RAM (random access memory) and swap memory.

Swap memory is a part of hard disk drive that acts like a virtual RAM.

# Syntax:
````
free
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/114d19fd-0a03-48e5-b501-20d1cfd46402)

Look at the above snapshot,

````Line1```` tells about the memory details like total RAM available in our system, used RAM, free RAM, shared RAM, buffered RAM and cached RAM.

````Line2```` indicates used and free buffer/cache memory.

````Line3```` indicates total, used and free swap memory.

# Displaying RAM in different format
By default, free command displays RAM information in kb format. You can display it in different format as per your wish.

# Syntax:
````
free -b     display information in Bytes  
free -m     display information in Megabytes  
free -g     display information in Gigabytes  
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/519308ae-caaa-4baa-bdee-a405da280486)

# free options

````
Option	                                 Function
free -t	                                  Display total memory
free -o	                                  Disable buffer adjusted line
free -s <time>	                          To update RAM at regular intervals
free -l	                                  Display high and low memory size statistics
watch free	                              Allows iterations
````
