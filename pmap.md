# pmap
The command pmap reports memory map of one process or multiple processes. It displays information about memory usage and address space of a process. To check pmap of a process we need PID of the process.

Syntax:
````
pmap PID  
````
Example:

pmap 2390

![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/17bfbc87-f453-49fd-8e17-0de566e225bd)

Look at the above snapshot, it shows memory map of PID 2390.

Memory map of multiple processes
Memory map of multiple processes can also be seen with the same command.

Syntax:
````
pmap PID1 PID2 PID3 . . .   
````
Example:

pmap 1682 2390

![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/7146ccd5-eacf-48a1-a989-22e30bb48ea2)

Look at the above snapshot, we have used PID 1682 and 2390. First information about PID 1682 is displayed then information about PID 2390 is displayed.

# Options :
````
-x	Show extended format
-d	Show device format
-q	Do not display header/footer line
-v	Version display
````
