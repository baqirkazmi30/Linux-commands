
### :diamond_shape_with_a_dot_inside: <a name="Linux Commands">Linux Commands</a>

<details>

- <b>tcpdump:</b> it is used to capture tcp/ip packets that transfered or received over a network on a specific interface.
- <b>Examples</b> 
  * tcpdump -c 5 -i ens3, capture 5 packets on interface ens3
  * tcpdump -D, Display list of available interfaces on system.
  * tcpdump -i ens3 tcp, only capture the tcp packets on interface ens3.

</details>

<details>

- <b>man:</b>it is used to retrive information in manual & display it as a text output on your screen.
- <b>Examples</b>
  * man ifconfig, it will display manual of 'iconfig' command on screen.
  * man tcpdump , it will display manual of 'tcpdump' command on screen.

</details>

<details>

- <b>Zip:</b>it is used to compress the files to reduce the size & also used as file package utility.
- <b>Examples</b>
  * zip myfile1.zip myfile.txt, it will create .zip file of myfile.txt file.
  * zip -r newfolder.zip myfolder/, it will create .zip file of myfolder.

</details>

<details>

- <b>dpkg:</b>it is main package management program in debian & debian based system.it is used to install,build,remove & manage packages.
- <b>Examples</b>
  * dpkg -i package_name.deb, it will install the package.
  * dpkg -r package_name.deb, it will remove the package.
  * dpkg -l ,it will show the list of installed packages.

</details>

<details>

- <b>Apt-get:</b>it is command line tool for working with APT software packages.
- <b>Examples</b>
  * apt-get install git, it will install git package in your system.
  * apt-get remove yum, it will remove yum package from your system.

</details>

<details>

- <b>Scp:</b>it allows files to be copied to,from or between different hosts.
- <b>Examples</b>
  * scp myfile.txt root@remotehost:/root, it will copy the file from local host to root directory of remotehost.
  * scp -r mydir root@remotehost:/Desktop, it will copy the whole directory from local host to Desktop of remotehost.

</details>

<details>

- <b>unzip:</b>it is used to extract compressed files in a zip archive.
- <b>Examples</b>
  * unzip myfile.zip, it will unzip the zip file.
  * unzip myfolder.zip, it will unzip the zip folder.

</details>

<details>

- <b>Touch:</b>it is used to change the file timestamps & also use to create empty files.
- <b>Examples</b>
  * touch -a myfile.txt, it will change the access of myfile.txt
  * touch -m myfile.txt, it will change the modify of myfile.txt

</details>

<details>

- <b>Sudo su:</b>it prompt you to your username and password.
- <b>Examples</b>
  * sudo su root, it will prompt user to root.
  * sudo su baqir,it will prompt user to baqir.

</details>

<details>

- <b>ssh:</b>it provides a secure encrypted connection between two hosts over a network.
- <b>Examples</b>
  * ssh user@remotehost, it will connect you with remote host.
  * ssh -v user@remotehost, it will show you debugging on remotehost.

</details>

<details>

- <b>chmod:</b>it is used to change the permission of file.
- <b>Examples</b>
  * chmod 777 myfile.txt, it means you allow everyone to read,write & execute that file.
  * chmod 755 myfile.txt, it means you allow everyone to read and execute that file.

<details>

<details>

- <b>ping:</b>it is used to check connectivity between two nodes.
- <b>Examples</b>
  * ping -c 10 172.30.222.151, it send 10 packets to 172.30.222.151
  * ping -i 5 google.com, it will wait 5 second before sending packets to ggogle.com

</details>

<details>

- <b>tar:</b>it is used to create compressed archive files.
- <b>Examples</b>
  * tar -xvzf myfile.tar.gz, it will extract tar files out of tar.gz archive.
  * tar -xvzf myfile.tar.gz -C /Desktop ,it will extract tar files to specific folder.

</details>

<details>

- <b>top:</b>it is used to allow users to monitor processes and system resource usage on linux.
- <b>Examples</b>
  * top -u baqir ,it will show specific user 'baqir' processess & resource usages.
  * top -n 2 , top command refreshes untill you quit. running this command top will refresh only 2 times.

</details>

<details>

- <b>ifconfig:</b>it is used to initialize an interface, assign ip address to an interface & enable or disable interface on demand.
- <b>Examples</b>
  * ifconfig ens3, it will show information of ens3 interface.
  * ifconfig ens8 up, it will enable interface ens8. 

</details>

<details>
  
- <b>grep:</b> it processes text line by line & prints any lines which match a specified pattern.
- <b>Examples</b>
  * grep "baqir" myfile.txt ,it will search baqir in file.
  * grep -n “linux*” myfile.txt ,it will display line number which contain linux.

</details>

<details>

- <b>gcc:</b>it used for compilation of C code.
- <b>Examples</b>
  * gcc file.c , it will executes the complete compilation process and outputs an executable with name a.out in same directory.
  * gcc file.c -o main ,it will executes the complete compilation process & produce an output file with name ‘main’ in same directory.

</details>

<details>

- <b>ps:</b>it is used to provide information about the currently runnning processes including their PID's.
- <b>Examples</b>
  * ps , it will display all processes running on current machine.
  * ps -fp 17796,18277 , it will make selection of mentioned PID's.

</details>

<details>

- <b>pkill:</b>it allows user to kill the program simply by specifying the name.
- <b>Examples</b>
  * pkill processname , it will kill the mentioned process.
  * pkill -f httpd ,  it will kill them all using -f option

</details>

<details>

- <b>find:</b>it is used to find files & directories & perform subsequent operations on it.
- <b>Examples</b>
  * find . -name myfile.txt ,it will find the directory in which file exists.
  * find / -type d -name task, it will find all the directories with the name task.

</details>

<details>

- <b>history:</b>it is used to show user recently used commands.
- <b>Examples</b>
  * history 5 , it will display last 5 command which recently used.
  * history -c, it will clear all the commands whicha re recently used.

</details>

<details>

- <b>echo:</b>In bash & C shell echo command writes its arguments to standard output.
- <b>Examples</b>
  * echo "my name is baqir" , it will print the string on screen.
  * echo nameserver 8.8.8.8 >> myfile.txt ,it will write nameserver 8.8.8.8 in file.

</details>

<details>
 
- <b>export:</b>it marks an environment variable to be exported with any newly forked child processes.it allows child process to inherit all marked variables.
- <b>Examples</b>
  * export -p ,it will export all the variable of current shell.
  * export EDITOR=/usr/bin/vim , it will set vim as a text editor.

</details>

<details>

- <b>passwd:</b>it is used to change the user password.
- <b>Examples</b>
  * sudo passwd baqir, it will change the password of user.
  * passwd -d baqir, it will delete the password of user.

</details>

<details>

- <b>iptables:</b>it is used to setup, maintain, & inspect the tables of ipv4 packet filter rules in linux kernal.
- <b>Examples</b>
  * iptables -F ,it will clean-up all the default rules, and existing rules
  * iptables -L ,it will list the default table rules.

</details>

<details>

- <b>insmod:</b>it is used to insert a module into the linux kernal.
- <b>Examples</b>
  * insmod dummy type="wpa" debug=1 , it will insert the module dummy to the kernal with two arguments type and debug.
  * insmod lp, it will insert the module lp to the kernal.

</details>

<details>

- <b>lsmod:</b>it shows which loadable kernal modules are currently loaded.
- <b>Examples</b>
  * lsmod | grep ppdev ,it will display the information of ppdev module.
  * lsmod , it will display all the kernal modules of machine.

</details>

<details>

- <b>rmmod:</b>it is used to unloads loadable modules from the running kernal.
- <b>Examples</b>
  * rmmod lp , it will remove kernal module lp.
  * rmmod ttm, it will remove kernal module ttm.

</details>

- <b>ls:</b>it is used list all the files of current working directory.
- <b>Examples</b>
  * ls -a, it will list all the files including hidden files of current directory.
  * ls -ls Desktop/, it will list the Desktop inforamtion.

<details>

- <b>mv:</b>it is used to move files from one directory to another.
- <b>Examples</b>
  * mv myfile.txt /root/downloads, it will move file from current diectory to /root/downloads.
  * mv my*.txt /root/documents, it will move multiple files having name 'my' from curent directoy to /root/documents.

</details>

<details>

- <b>cp:</b>it is used to copy files from one directory to another.
- <b>Examples</b>
  * cp myfile.txt /root/downloads/newfile.txt, it will copy file to /root/downloads with rename 'newfile.txt'.
  * cp -n myfile.txt ~/root/Desktop/, it will not overwrite the existing file. 

</details>

<details>

- <b>rm:</b>it is used to remove files & directories.
- <b>Examples</b>
  * rm myfile.txt, it will remove file.
  * rm -rf task, it will remove task directory.

</details>

<details>

- <b>mkdir:</b>it is used to create new directory.an:it is used to retrive information in manual & display it as a text output on your screen.
- <b>Examples</b>
  * mkdir linux_dir, it will make new directory 'linux_dir' in current directory.
  * mkdir dir1 dir2 dir3, it will create multiple directories in current directory.

</details>

