# DS - ucDrive

<br>

## Description
Development of a shared file storage platform for students and teachers, including data storage with client-server architecture, multithreaded model for designing servers, sockets for communication between clients and servers, administration console using Java RMI, guarantee of application availability through redundancy with mechanisms of failover.

### Technologies:
- Java
- Sockets
- Threads
- RMI

<br>

## Information
To run ucDrive, the following steps must be followed:
- Create a directory for server 1 (with the name, for example, server1)
- Place the server.jar inside this
- Within it, create a board that must have the name home
- Within the home directory created, place the config.txt and clients.txt files, which must have the structure indicated in the report (attached, in the configs directory, are two config.txt files that can be used, config.txt and otherconfig.txt, remembering that when placing the otherconfig.txt file it must be changed to config.txt)
- Repeat the same process for server 2

At this point this should be the current structure:

	server1
	|
	+---home
	|    |
	|    +---clients.txt
	|    +---config.txt
	|
	+---server.jar

	server2
	|
	+---home
	|    |
	|    +---clients.txt
	|    +---config.txt
	|
	+---server.jar

- Create a directory for the client (with the name, for example, client1)
- Place the client.jar inside this
- Within it, create a board that must have the name home
- Repeat the same process for as many customers as you want

At this point this should be the current structure:

	Client1
	|
	+---home  
	|
	+---client.jar

- For the admin, it is only necessary to run admin.jar, however you can place it within a directory also for organizational reasons

After these steps, you need to open a terminal for each .jar in the previously created directories, running java -jar "file".jar

Keep in mind that you must initialize the servers first and only then the admin and clients.


In case of any doubts, the structure mensioned above can be found in the directory:

	structure/

### Note
To generate the .jar files it was used jdk 17. For compatibility reasons it is recommended to use this version to run them.

In the Windows operating system, it was found that multiple functionalities may present anomalies. However, on macOS this does not happen.

<br>

## Authors: 
- Miguel Faria
- João Monteiro
- António Correia