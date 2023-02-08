# Automation bash script
![maxresdefault](https://user-images.githubusercontent.com/102508387/216788886-0703921c-bafa-4af7-a09b-c5a1165544d7.jpg)

:heavy_dollar_sign: Linux_USER_creation: 

  ● The goal of this exercise is to create a shell script that adds users to the same Linux system .
 1) Enforce that it be executed with superuser (root) privileges.
 2) Use the first argument provided on the command line as the username for the account.
 3) Automatically generate a password for the new account .
 4) Inform the user if the account was not able to be created for some reason.
 5) Display the username, password, and host where the account was created.
 
 ![sc1](https://user-images.githubusercontent.com/102508387/216790190-c866a7ed-b49e-4d72-ab2a-02d5877d562a.png)

:heavy_dollar_sign: Deleting_Local_Users:

  ● The goal of this script is to create a shell script that allows for a local Linux account to be
disabled, deleted, and optionally archived.
1) Enforce that it be executed with superuser (root) privileges. 
2) Provide a usage statement much like you would find in a man page 
3) Allow the user to specify options
4) Accept a list of usernames as arguments. At least one username is required or the script
5) Refus to disable or delete any accounts that have a UID less than 1000
6) nform the user if the account was not able to be disabled, deleted, or archived for some
reason.
7) Displays the username and any actions performed against the account.

![dis3](https://user-images.githubusercontent.com/102508387/217295497-74cac291-74d1-4709-b176-3de91eb4e0ae.png)

:heavy_dollar_sign: command_everyWhere : 

  ● The goal of this script is to create a shell script that executes a given command on multiple servers.
  1) Execute all arguments as a single command on every server listed in the /vagrant/servers file by default.
2) Execute the provided command as the user executing the script.
3) Use "ssh -o ConnectTimeout=2" to connect to a host. This way if a host is down, the scriptdoesn't hang for more than 2 seconds per down server.
4) Allow the user to specify options
5) Enforce that it be executed without superuser (root) privileges. 
6) Provide a usage statement much like you would find in a man page if the user does not supply a command to run on the command line and returns an exit status of 1.
7) Inform the user if the command was not able to be executed successfully on a remote host
8) Exit with an exit status of 0
