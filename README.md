# shell-scripting-with-CodeSignal
System Automation with Shell Scripts
UNIT 1 Package Management
Task 1: Write a shell script from scratch. The script should:
List all installed packages and save them to a file package_list.txt
Update the list of available packages and save the output to updated_list.txt
Simulate an upgrade by showing the packages that will be upgraded and saving this output to upgrades.txt.
Print out the contents of all three files. You can use the cat command to print the contents of a file.

UNIT 2 User Management
Task 2: Write a script that performs user management. This script:
Prints the list of users to users.txt
Shows the current user, their home directory, and shell.
Adds a new user named and sets up their home directory.
Switches to the new user and shows their environment details.
Run the script to observe the output of creating a new user. 

Task 3: Write a shell script that:
Create and add two new users named Cosmo and Nova.
User Cosmo should have the home directory path $PWD/users/spaceship.
User Nova should have the home directory path $PWD/users/galaxy.
Hint: You can use -d pathname to set the user's homedir
Print the relevant entries for both users from the /etc/passwd file to verify their creation.
List the users folder to show the homedirs

UNIT 3 Disk Usage Monitoring
Task 4: Write a script that uses the df and du commands to check disk usage. Here is what the script does:
It monitors a directory named /tmp.
Uses the df command to show disk space usage of the filesystem.
Uses the du command to display disk usage of files and directories.
Creates a large file and rechecks disk usage statistics.
Run the script to see how it gathers and displays disk usage info.

UNIT 4 Scheduling Tasks with Cron
Task 5: Create and automate a shell script that checks disk usage daily and appends this information to a log file. You will utilize cron jobs to schedule the script to run automatically every weekday at 9 A.M. Follow the TODO comments to correctly schedule the check_usage.sh file.
In check_usage.sh, append the following to the output file:
The current date
Human readable disk usage statistics for the CWD (use df)
