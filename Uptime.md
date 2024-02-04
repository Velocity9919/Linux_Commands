# Linux uptime
The uptime command tells us how long a system has been running.

Syntax:
````
uptime  
````
![image](https://github.com/Velocity9919/Linux_Commands/assets/143435067/8274e145-7048-4c58-b17b-13b7651fec0c)


Look at the above snapshot, command "uptime" displays output in one line.

From the left, it shows,

-> currrent system time
-> duration for which system has been running (system is running since 18 minutes)
-> number of users logged in (2 users are logged in)
-> system load average CPU load for past 1, 5 and 15 minutes.

Here, system load averages are the processes which are either in runnable or in uninterruptable state.

A runnable process may be either a running one using CPU or waiting to use CPU. An uninterruptable process is waiting for some I/O access.

# Option

Command uptime has a single option.
````
Uptime -V
````
It displays version information.
