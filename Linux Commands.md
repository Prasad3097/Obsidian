

```bash

ls #List directory contents.
top #To check CPU processes.
ls ./* #Print the all files with its contents.
grep #Find specific word.
cat access.log | grep "THM" #Find specific string of file.
mkdir -p #To create the parent directories.
ls -a #Shows the hidden files 
ls -la #lists the contents of your current working directory.
cd #Change directory.
pwd #Print working directory (displays the current directory path).
mkdir #Make directories. mkdir new_directory
echo oldFileName >> NewFileName #Replace content of file name.
rmdir #Remove empty directories. rmdir directory_name
whoami #Find out what user we're currently logged in as!
rm #Remove files or directories. `rm -r directory_name`
ls -l #displays various information related to file permission.
ls -al #show the hidden files with long format.
cat ./- # Display the contents of the file.
mv #Rename to directory name.
du #To check the information of disk usage of files and directories on a system.
ls -la -R #listing contents inside a directory.
df -h #To check the available disks.
wc #To get a count of the total number of lines, words, and characters contained in a file.
cd ~ #Use `cd` command to go to the home directory.
/bin #important binary applications.
/etc #configuration files, startup scripts, etc.
/home #List of home directories for different users.
/lib #system libraries, shared libraries.
/mnt #manually mounted filesystems on your hard drive.
/sys #System files.
/tmp #Temporary files.
chgrp #The chgrp command stands for change group" and is used to change the group of a file.
chown #The chown command stands for "change owner" and is used to change the owner of a file.
/var #variable files such as logs and databases.
 cd ../ #move one directory to another directory.
 cd ~ #Go to direct your home directory.
 cd - #To go in your last directory.

'''


'''bash
File Permissions
Using chmod with absolute permission

Number Octal Permission Representation Ref
0 #No permission
1 #Execute permission --x
2 Write permission -w-
3 Execute and write permission: 1 (execute) + 2 (write) = 3  -wx
4 Read permission|r--|
5 Read and execute permission: 4 (read) + 1 (execute) = 5  r-x
6 Read and write permission: 4 (read) + 2 (write) = 6  rw-
7 All permissions: 4 (read) + 2 (write) + 1 (execute) = 7  rwx
'''






