

```bash

ls #List directory contents.
top #To check CPU processes.
ls ./* #Print the all files with its contents.
grep #Find specific word.
cat access.log | grep "THM" #Find specific string of file.
cp filename DirectoryName #Copy file and paste to directory.
cp DirectoryName/fileNmae DirectoryName/ #Copy data one directory to another directory.
 mv newfile.txt ../cloud/ #move file into previous directory.
 wc filename #Shows the number of lines , number of words , number of                m bytes.
mkdir -p #To create the parent directories.
ls -a #Shows the hidden files 
ls -la #lists the contents of your current working directory.
cd #Change directory.
zcat #Display content of zip file.
head -n 5 filename #Display the output of first five lines.
tail -n 5 filename #Display the output of last five lines.
tail -f #Displays the new updated data.
less filename #Displays files on page format.
more filename #Display files in page format.
pwd #Print working directory (displays the current directory path).
mkdir #Make directories. mkdir new_directory
echo oldFileName >> NewFileName #Replace content of file name.
rmdir #Remove empty directories. rmdir directory_name
whoami #Find out what user we're currently logged in as!
rm #Remove files or directories.
rm -r #Remove directory with files.
ls -l #displays various information related to file permission.
ls -al #show the hidden files with long format.
cat ./- # Display the contents of the file.
vmstat -a #Details of active & inactive virtual memory.
mv #Rename to directory name.
du #To check the information of disk usage of files and directories on a system.
free -h #Details of Disk space.
nohup #Store the any command output. 
ls -la -R #listing contents inside a directory.
df -h #To check the available disks.
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
cut -b 1-6 s.txt #Cut byte and display text.
 ln -s /home/prasad/cloud/s.txt softlink-file #Create Softlink.
 ln  /home/prasad/cloud/s.txt  hardlink-file  #Create Hardlink.
 ls -ltr #shows the softlink file location.
 echo "Rushi" | tee abc.txt #At one time display output to screen and create file.
 du . #Display folders in current directory.
 sort filename #Sort file alphabetic order. 
 diff a.txt abc.txt #Difference between two files.
 wc #To get a count of the total number of lines, words, and characters contained in a file.
 (diff between 2 files use diff & difference between multiple files use wc)

System level commands
 uname #Shows the platform currently you are using.
 uptime #Shows the total work time of your system.
 date #Displays the date.
 who #Displays the usrer's login history.
 whoami #Displays the current user.
 which #Shows the your command location. 
 id #Shows the your system users and groups.
 sudo #Super user.
 shutdown #System shutdown.
 reboot #Restart the system.
 apt #install new software packages, upgrade existing software packages, update the package list index, and even upgrade the entire Ubuntu system.


User & Group Management Command.
sudo useradd -m rushi #Add the user.(-m #Make directory.)
sudo userdel rushi #Delete the user.
sudo cat /etc/passwd #List of Adding users.
sudo groupadd tester #Add the group.
sudo gpasswd -a rushi tester #Add user in tester group.
sudo gpasswd -M user1,user2,user3 tester #Add multiple user at one                                              time.
sudo groupdel tester #Delete the group.
sudo cat /etc/group #List of group users.
sudo passwd rushi #Assign password to rushi.
su rushi #Switch user.


'''


'''bash
File Permissions
Using chmod with absolute permission
chmod 777 directoryname #Change the file permission.
umask #Bydefault permission assign to user at the time of file                creation.
sudo chown username Dir_OR_Filename #Change owner of file or directory.
sudo chgrp groupname filename #Change the groupname of file.
zip -r lfd.zip linux-for-devops/ #File convert to zip format.
unzip lfd.zip #unzip file.
sudo apt install #install the utility.

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






