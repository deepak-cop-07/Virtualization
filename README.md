# Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands```
NAME: S DEEPAK KUMAR
REG NUMBER: 212223060039
Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

3.a) Installation and Configuration of Oracle VirtualBox
Aim:
To install and configure Oracle VM VirtualBox.

Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
Steps:
1.Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
2.Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
3.Configure VirtualBox:

Open VirtualBox.

Click New → Name VM → Select Type (Linux/Windows) and Version.

Allocate:

Minimum 2 GB RAM

Create Virtual Hard Disk (20 GB recommended).

Start Virtual Machine and provide ISO to install OS.

Result:
Thus, Oracle VM VirtualBox was installed successfully.

3.b) Installation and Configuration of Kali Linux
Aim:
To install and configure Kali Linux in Oracle VirtualBox.

Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
Steps:
1.Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
2.Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:
Minimum 2 GB RAM (recommended 4 GB).
4.Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
5.Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
6.Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
7.Login to Kali Linux:

Use root credentials.
8.(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox image
<img width="927" height="497" alt="image" src="https://github.com/user-attachments/assets/4807fcf5-8463-4404-a719-eccd5afc192c" />

Snapshot 2: Kali Running in Virtual image
<img width="935" height="573" alt="image" src="https://github.com/user-attachments/assets/032cc882-3a20-430c-99b8-e9999ff6ba6f" />

Result:
Thus, Kali Linux guest OS was installed and configured successfully.

3.c) Execution of Linux Commands in Kali
About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
Commands:
1) ls Command
   
   <img width="855" height="68" alt="image" src="https://github.com/user-attachments/assets/152a3fb6-0cb6-4466-8fc5-e7975d941ed1" />

The ls command is used to display a list of content of a directory.

Syntax: ls

cs1
2) pwd Command
<img width="250" height="67" alt="image" src="https://github.com/user-attachments/assets/88960127-54ac-47c7-87eb-9c4dd804a6be" />

The pwd command is used to display the location of the current working directory.

Syntax: pwd

cs2
3) mkdir Command
<img width="930" height="116" alt="image" src="https://github.com/user-attachments/assets/72d966de-e03f-4ba1-8321-d4635d05f6d8" />

The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

cs3
4) rmdir Command
<img width="888" height="127" alt="image" src="https://github.com/user-attachments/assets/a218dbb0-657e-47eb-a24d-ebd55c805069" />

The rmdir command is used to delete a directory.

Syntax: rmdir

cs4
5) cd Command
<img width="354" height="158" alt="image" src="https://github.com/user-attachments/assets/5ee8703a-0354-4ed9-976e-1c0f902d04dc" />

The cd command is used to change the current directory.

Syntax: cd

cs5
6) cat Command
<img width="350" height="183" alt="image" src="https://github.com/user-attachments/assets/4d857551-d6d4-4339-a769-7259420a0c5a" />

The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

cs6
7) cp Command


<img width="334" height="133" alt="image" src="https://github.com/user-attachments/assets/620680cd-af78-4176-aed9-cbde90f5d025" />

The cp command is used to copy a file or directory.

Syntax: cp

cs7
8) gedit Command

<img width="501" height="40" alt="image" src="https://github.com/user-attachments/assets/544376f2-2a55-42b6-b31f-250848cd5e18" />

The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

cs8
9) su Command

<img width="296" height="88" alt="image" src="https://github.com/user-attachments/assets/d3235dd1-2dbb-4017-a137-949cf69d4484" />

The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

cs9
10) mv Command

<img width="363" height="265" alt="image" src="https://github.com/user-attachments/assets/13677227-627c-410a-af3c-e838a0a20aaf" />

The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

cs10
11) rename Command

<img width="462" height="171" alt="image" src="https://github.com/user-attachments/assets/f624809f-756c-498a-a751-707a0f214608" />

The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

cs11
12) head Command

<img width="394" height="528" alt="image" src="https://github.com/user-attachments/assets/1128e604-6a2b-4d01-bdc2-a81d50e209e7" />

The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

cs12
13) tail Command

<img width="303" height="243" alt="image" src="https://github.com/user-attachments/assets/e709b876-408a-469d-aa17-afcd492aedc3" />

The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

cs13
14) id Command

<img width="841" height="48" alt="image" src="https://github.com/user-attachments/assets/3ce18f5c-f0f3-4d5d-aba1-5f92a46aa677" />

The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

cs14
15) grep Command

<img width="345" height="77" alt="image" src="https://github.com/user-attachments/assets/8e5eb2bc-7c7c-48cc-8a8b-ce08285d7957" />

The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

cs15
16) tr Command

<img width="465" height="308" alt="image" src="https://github.com/user-attachments/assets/5725511b-e2ad-460d-be49-65dffd3b45e2" />

The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

cs16
17) chmod Command

<img width="455" height="127" alt="image" src="https://github.com/user-attachments/assets/128af50a-a8a4-4f83-a43d-ba7b57f8a540" />

The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

cs17
18) tar Command

<img width="378" height="157" alt="image" src="https://github.com/user-attachments/assets/a67af1ae-aebf-4e47-a8bc-d5ef47c74dee" />

The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

cs18
19) chown Command\

<img width="471" height="129" alt="image" src="https://github.com/user-attachments/assets/f133af5d-1f12-4445-8031-c5abae2386be" />

The chown command is used to change ownership.

Syntax: chown owner_name file_name

cs19
20) make Command

<img width="233" height="70" alt="image" src="https://github.com/user-attachments/assets/1959a121-5a46-4945-981f-85e446e5a2f9" />

The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

cs20
21) ifconfig Command

<img width="864" height="117" alt="image" src="https://github.com/user-attachments/assets/dc311e2d-6602-4d4e-8931-2ec47e5dd5af" />

The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

cs21
22) chmod 777 Command

<img width="492" height="126" alt="image" src="https://github.com/user-attachments/assets/d4d95912-6326-45ed-bc7e-2d03bc477667" />

The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

cs22
23) host Command

<img width="630" height="108" alt="image" src="https://github.com/user-attachments/assets/13aa754f-4599-4040-9205-2c6b98ddda36" />

The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

cs23
24) gzip Command

<img width="843" height="136" alt="image" src="https://github.com/user-attachments/assets/694f7455-f3a5-4342-986e-a08607d51d97" />

The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

cs24
25) sort Command

<img width="331" height="312" alt="image" src="https://github.com/user-attachments/assets/c06ee9db-ee38-4dc5-a014-06605a883fec" />

The sort command is used to sort files in alphabetical order.

Syntax:sort

cs25
26) cal Command

<img width="712" height="286" alt="image" src="https://github.com/user-attachments/assets/960d7067-e9ac-42f1-aefa-04a114b4ad4c" />

The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

image
27) clear Command

<img width="823" height="791" alt="image" src="https://github.com/user-attachments/assets/8fd637fb-c01b-44c6-a9a0-8f04e990d9dc" />

Linux clear command is used to clear the terminal screen.

Syntax: clear

image image
28) mail Command

<img width="751" height="83" alt="image" src="https://github.com/user-attachments/assets/c077e7d9-7698-4bc6-a8a8-4a990e48b1fe" />

The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

cs28
29) df Command

<img width="833" height="272" alt="image" src="https://github.com/user-attachments/assets/6fdc1999-bd6e-42e9-9960-9c5c22c21863" />

The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

cs29
30) find Command

<img width="686" height="114" alt="image" src="https://github.com/user-attachments/assets/1b3c90b2-6340-401f-bfde-379a88134ef8" />

The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

Result:

Thus, the execution of various Linux commands is executed successfully using Kali Linux.
