Killport
Killport is a simple bash script for Mac that allows you to kill the process that's using a specific port. It's useful when you need to free up a port that's being used by a process you no longer need.

Installation
Download the script in your computer

Make the script executable:
chmod +x ~/killport

Move the script to a directory that's in your PATH, such as /usr/local/bin:
mv ~/killport /usr/local/bin/killport

Usage
To use the killport command, simply type killport followed by the port number. For example, to kill the process using port 8080, you would use the following command:

killport 8080

Please note that this script will only be able to kill processes that are owned by your user, unless you run it with sudo. Be careful when killing processes, as it can cause data loss or other problems if you kill a process that's doing something important.