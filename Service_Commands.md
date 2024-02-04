# Linux service
The service command starts, stop and restart a daemon or services by calling the script. Usually all scripts are stored in /etc/init.d directory.

It runs a script in as predictable environment as possible.

Syntax:
````
service script_name command
````
Here, command can be anyone from start, stop, restart and status.
# stop command

To stop a service use the following syntax,

Syntax:
````
service script_name stop  
````
# start command

To start a service use the following syntax,

Syntax:

service script_name start  

# restart command

To restart a service use the following syntax,

Syntax:
````
service script_name restart  
````
# status command

To get current status of a service use the following syntax,

Syntax:
````
service script_name status
````
