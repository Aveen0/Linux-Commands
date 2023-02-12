Linux Commands for Beginners

What is Linux?
Let’s start with very basic question. What is Linux? Basically, it is an open-source operating system. Now the next questions that come to one’s mind are what is meant by open source and what is an operating system? An operating system is a software that manages the communication between the hardware components of the components and the user. It also manages the assignment of tasks to different hardware components. And since this software is available for anyone to use and make changes to, as per their requirements, it is called an open source software. 

Why we need Linux commands?
Linus is a command line interface (CLI). Which means that it receives text inputs in order to execute certain functions of the operating system. Hence, Linux has commands for creating files, navigating directories and much more. 

Here we will be going through a few of the basic Linux commands. 
Starting off with command to know your current location in the directory, move from one directory to another and to create files and directories:

•	‘pwd’ command: 
By running this command on the terminal, you will be made aware of your location in the file system. What this basically means is that if you were to create a file right now, then where would it be created in the system. 
Once you run this command a path will be displayed on the terminal e.g., home/user11. This means that the directory the user is currently in is ‘home’ directory and the folder in which he is in is ‘user11’. 

•	‘ls’ command: 
This command will tell you about the files in the current the directory. How so? Basically, once you run this command on the terminal it will display a list of names of the files present in the current directory that you are in. However, it does not display the hidden filenames. 

•	‘mkdir’ command: 
This command is used to create a new directory within the current directory. However, if you want to create a new directory at another location then you will have to provide the path for the location after the command. For example, suppose you want to create a new directory in a directory called N1, then the command you need to write is mkdir /N1/newDirectoryName and this will create a new directory called ‘newDirectoryName’ in the directory N1.

•	‘cd’ command: This command is actually used to move from one location in the system to another. For example, if you want to move to a folder in home then the command you need to run is cd /home/folder1. 

•	‘touch’ command: This command is used to create files in Linux.  For example, once you run touch newfile.txt it will create a new file named ‘newfile’ in your current directory.

•	‘cat’ command: This command can be used to display the content of a file on the terminal. Hence you can see what is in the file without actually having to view the file. For example, if you write cat file1.txt it will display the contents of this file on the terminal.

•	‘kill’ command: This command is used to manually kill any processes that might be running and taking up too many resources. In order to kill a specific process, you need to specifically provide the ID of that process you want to kill.

•	‘cp’ command: This command is used to copy files and directories from one location to another. So, for this command you need to have the current location’s path that is the source location and the destination location’s path. For example, cp [SOURCE] [DESTINATION].

•	‘sudo’ command: This is one of the most important Linux commands. Basically, when you run this command as a prefix with any other command then it runs the command with elevated privileges and by elevated privileges it means those of root user which are required for some commands. 

