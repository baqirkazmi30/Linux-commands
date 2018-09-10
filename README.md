
### :diamond_shape_with_a_dot_inside: <a name="Linux Commands">Linux Commands</a>

<details>
<summary><b>Tcpdump</b></summary>
- <b>tcpdump:</b> it is used to capture tcp/ip packets that transfered or received over a network on a specific interface. </br>
- <b>Examples</b> </br>
  * tcpdump -c 5 -i ens3, capture 5 packets on interface ens3 </br>
  * tcpdump -D, Display list of available interfaces on system. </br>
  * tcpdump -i ens3 tcp, only capture the tcp packets on interface ens3. </br>

</details>

<details>
<summary><b>man</b></summary>
- <b>man:</b>it is used to retrive information in manual & display it as a text output on your screen. </br>
- <b>Examples</b> </br>
  * man ifconfig, it will display manual of 'iconfig' command on screen. </br>
  * man tcpdump , it will display manual of 'tcpdump' command on screen. </br>
</details>

<details>
<summary><b>zip</b></summary>
- <b>Zip:</b>it is used to compress the files to reduce the size & also used as file package utility. </br>
- <b>Examples</b> </br>
  * zip myfile1.zip myfile.txt, it will create .zip file of myfile.txt file.</br>
  * zip -r newfolder.zip myfolder/, it will create .zip file of myfolder. </br>
</details>

<details>
<summary><b>dpkg</b></summary>
- <b>dpkg:</b>it is main package management program in debian & debian based system.it is used to install,build,remove & manage packages.</br>
- <b>Examples</b></br>
  * dpkg -i package_name.deb, it will install the package.</br>
  * dpkg -r package_name.deb, it will remove the package.</br>
  * dpkg -l ,it will show the list of installed packages.</br>
</details>

<details>
<summary><b>apt-get</b></summary>
- <b>Apt-get:</b>it is command line tool for working with APT software packages.<br>
- <b>Examples</b><br>
  * apt-get install git, it will install git package in your system.</br>
  * apt-get remove yum, it will remove yum package from your system.</br>
</details>

<details>
<summary><b>scp</b></summary>
- <b>Scp:</b>it allows files to be copied to,from or between different hosts.
- <b>Examples</b>
  * scp myfile.txt root@remotehost:/root, it will copy the file from local host to root directory of remotehost.
  * scp -r mydir root@remotehost:/Desktop, it will copy the whole directory from local host to Desktop of remotehost.
</details>

<details>
<summary><b>unzip</b></summary>
- <b>unzip:</b>it is used to extract compressed files in a zip archive.
- <b>Examples</b>
  * unzip myfile.zip, it will unzip the zip file.
  * unzip myfolder.zip, it will unzip the zip folder.
</details>

<details>
<summary><b>Touch</b></summary>
- <b>Touch:</b>it is used to change the file timestamps & also use to create empty files.
- <b>Examples</b>
  * touch -a myfile.txt, it will change the access of myfile.txt
  * touch -m myfile.txt, it will change the modify of myfile.txt
</details>

<details>
<summary><b>sudo su</b></summary>
- <b>Sudo su:</b>it prompt you to your username and password.
- <b>Examples</b>
  * sudo su root, it will prompt user to root.
  * sudo su baqir,it will prompt user to baqir.
</details>

<details>
<summary><b>ssh</b></summary>
- <b>ssh:</b>it provides a secure encrypted connection between two hosts over a network.
- <b>Examples</b>
  * ssh user@remotehost, it will connect you with remote host.
  * ssh -v user@remotehost, it will show you debugging on remotehost.
</details>

<details>
<summary><b>chmod</b></summary>
- <b>chmod:</b>it is used to change the permission of file.
- <b>Examples</b>
  * chmod 777 myfile.txt, it means you allow everyone to read,write & execute that file.
  * chmod 755 myfile.txt, it means you allow everyone to read and execute that file.
<details>

<details>
<summary><b>ping</b></summary>
 <b>ping:</b>it is used to check connectivity between two nodes.
  <b>Examples</b>
  * ping -c 10 172.30.222.151, it send 10 packets to 172.30.222.151
  * ping -i 5 google.com, it will wait 5 second before sending packets to ggogle.com
</details>

<details>
<summary><b>tar</b></summary>
 <b>tar:</b>it is used to create compressed archive files.
   <b>Examples</b>
  * tar -xvzf myfile.tar.gz, it will extract tar files out of tar.gz archive.
  * tar -xvzf myfile.tar.gz -C /Desktop ,it will extract tar files to specific folder.
</details>

<details>
<summary><b>top</b></summary>
 <b>top:</b>it is used to allow users to monitor processes and system resource usage on linux.
   <b>Examples</b>
  * top -u baqir ,it will show specific user 'baqir' processess & resource usages.
  * top -n 2 , top command refreshes untill you quit. running this command top will refresh only 2 times.
</details>

<details>
<summary><b>ifconfig</b></summary>
 <b>ifconfig:</b>it is used to initialize an interface, assign ip address to an interface & enable or disable interface on demand.          <b>Examples</b>
  * ifconfig ens3, it will show information of ens3 interface.
  * ifconfig ens8 up, it will enable interface ens8. 
</details>

<details>
<summary><b>grep</b></summary>
 <b>grep:</b> it processes text line by line & prints any lines which match a specified pattern.
   <b>Examples</b>
  * grep "baqir" myfile.txt ,it will search baqir in file.
 ..*grep -n “linux*” myfile.txt ,it will display line number which contain linux.
</details>

<details>
<summary><b>gcc</b></summary>
  <b>gcc:</b>it used for compilation of C code.
   <b>Examples</b>
 * gcc file.c , it will executes the complete compilation process and outputs an executable with name a.out in same directory.
 * gcc file.c -o main ,it will executes the complete compilation process & produce an output file with name ‘main’ in same directory.
</details>

<details>
<summary><b>ps</b></summary>
 <b>ps:</b>it is used to provide information about the currently runnning processes including their PID's.
   <b>Examples</b>
  * ps , it will display all processes running on current machine.
  * ps -fp 17796,18277 , it will make selection of mentioned PID's.
</details>

<details>
<summary><b>pkill</b></summary>
 <b>pkill:</b>it allows user to kill the program simply by specifying the name.
   <b>Examples</b>
  * pkill processname , it will kill the mentioned process.
  * pkill -f httpd ,  it will kill them all using -f option
</details>

<details>
<summary><b>find</b></summary>
<b>find:</b>it is used to find files & directories & perform subsequent operations on it.
  <b>Examples</b>
  * find . -name myfile.txt ,it will find the directory in which file exists.
  * find / -type d -name task, it will find all the directories with the name task.
</details>

<details>
<summary><b>history</b></summary>
 <b>history:</b>it is used to show user recently used commands.
   <b>Examples</b>
  * history 5 , it will display last 5 command which recently used.
  * history -c, it will clear all the commands whicha re recently used.
</details>

<details>
<summary><b>echo</b></summary>
<b>echo:</b>In bash & C shell echo command writes its arguments to standard output.
  <b>Examples</b>
  * echo "my name is baqir" , it will print the string on screen.
  * echo nameserver 8.8.8.8 >> myfile.txt ,it will write nameserver 8.8.8.8 in file.
</details>

<details>
<summary><b>export</b></summary>
 <b>export:</b>it marks an environment variable to be exported with any newly forked child processes.it allows child process to inherit all marked variables.
   <b>Examples</b>
  * export -p ,it will export all the variable of current shell.
  * export EDITOR=/usr/bin/vim , it will set vim as a text editor.
  </details>

<details>
<summary><b>passwd</b></summary>
 <b>passwd:</b>it is used to change the user password.
   <b>Examples</b>
  * sudo passwd baqir, it will change the password of user.
  * passwd -d baqir, it will delete the password of user.
</details>

<details>
<summary><b>iptables/b></summary>
 <b>iptables:</b>it is used to setup, maintain, & inspect the tables of ipv4 packet filter rules in linux kernal.
   <b>Examples</b>
  * iptables -F ,it will clean-up all the default rules, and existing rules
  * iptables -L ,it will list the default table rules.
</details>

<details>
<summary><b>insmod</summary>
 <b>insmod:</b>it is used to insert a module into the linux kernal.
   <b>Examples</b>
  * insmod dummy type="wpa" debug=1 , it will insert the module dummy to the kernal with two arguments type and debug.
  * insmod lp, it will insert the module lp to the kernal.
</details>

<details>
<summary><b>lsmod</b></summary>
 <b>lsmod:</b>it shows which loadable kernal modules are currently loaded.
  <b>Examples</b>
  * lsmod | grep ppdev ,it will display the information of ppdev module.
  * lsmod , it will display all the kernal modules of machine.
</details>

<details>
<summary><b>rmmod</b></summary>
 <b>rmmod:</b>it is used to unloads loadable modules from the running kernal.
   <b>Examples</b>
  * rmmod lp , it will remove kernal module lp.
  * rmmod ttm, it will remove kernal module ttm.
</details>

<details>
<summary><b>ls</b></summary>
  <b>ls:</b>it is used list all the files of current working directory.
   <b>Examples</b>
  * ls -a, it will list all the files including hidden files of current directory.
  * ls -ls Desktop/, it will list the Desktop inforamtion.
</details>
<details>
<summary><b>mv</b></summary> 
  <b>mv:</b>it is used to move files from one directory to another.
   <b>Examples</b>
  * mv myfile.txt /root/downloads, it will move file from current diectory to /root/downloads.
  ..*mv my*.txt /root/documents, it will move multiple files having name my from curent directoy to /root/documents.
</details>

<details>
<summary><b>cp</b></summary>
 <b>cp:</b>it is used to copy files from one directory to another.
   <b>Examples</b>
  * cp myfile.txt /root/downloads/newfile.txt, it will copy file to /root/downloads with rename 'newfile.txt'.
  * cp -n myfile.txt ~/root/Desktop/, it will not overwrite the existing file. 
</details>

<details>
<summary><b>rm</b></summary>
  <b>rm:</b>it is used to remove files & directories.
   <b>Examples</b>
  * rm myfile.txt, it will remove file.
  * rm -rf task, it will remove task directory.
</details>

<details>
<summary><b>mkdir</b></summary>
 <b>mkdir:</b>it is used to create new directory.an:it is used to retrive information in manual & display it as a text output on your screen.
   <b>Examples</b>
  * mkdir linux_dir, it will make new directory 'linux_dir' in current directory.
  * mkdir dir1 dir2 dir3, it will create multiple directories in current directory.
</details>

