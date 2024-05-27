# Comprehensive List of CMD Commands

## File and Directory Commands

### `dir` : Lists the contents of a directory.
```shell
dir
```
Example:

```shell
dir C:\Users
```

### cd : Changes the current directory.

shell
Copy code
cd <directory>
Example:

shell
Copy code
cd C:\Windows\System32
md or mkdir
Creates a new directory.

shell
Copy code
md <directory>
mkdir <directory>
Example:

shell
Copy code
mkdir C:\NewFolder
rd or rmdir
Removes an empty directory.

shell
Copy code
rd <directory>
rmdir <directory>
Example:

shell
Copy code
rmdir C:\OldFolder
del or erase
Deletes one or more files.

shell
Copy code
del <file>
erase <file>
Example:

shell
Copy code
del C:\temp\oldfile.txt
copy
Copies one or more files to another location.

shell
Copy code
copy <source> <destination>
Example:

shell
Copy code
copy C:\file.txt D:\backup\file.txt
move
Moves one or more files from one directory to another.

shell
Copy code
move <source> <destination>
Example:

shell
Copy code
move C:\file.txt D:\backup\file.txt
rename or ren
Renames a file or directory.

shell
Copy code
rename <oldname> <newname>
ren <oldname> <newname>
Example:

shell
Copy code
rename C:\file.txt newfile.txt
xcopy
Copies files and directory trees.

shell
Copy code
xcopy <source> <destination> [options]
Example:

shell
Copy code
xcopy C:\source D:\destination /E /H /C /I
System Information Commands
systeminfo
Displays detailed configuration information about a computer and its operating system.

shell
Copy code
systeminfo
hostname
Displays the hostname of the computer.

shell
Copy code
hostname
tasklist
Displays a list of currently running processes on the local or a remote computer.

shell
Copy code
tasklist
taskkill
Ends one or more tasks or processes.

shell
Copy code
taskkill /F /IM <processname>
Example:

shell
Copy code
taskkill /F /IM notepad.exe
chkdsk
Checks a disk and displays a status report.

shell
Copy code
chkdsk [volume] [options]
Example:

shell
Copy code
chkdsk C: /F /R
Network Commands
ipconfig
Displays all current TCP/IP network configuration values and refreshes Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings.

shell
Copy code
ipconfig
ping
Sends ICMP Echo Requests to network hosts.

shell
Copy code
ping <hostname or IP address>
Example:

shell
Copy code
ping google.com
tracert
Traces the route to a remote host.

shell
Copy code
tracert <hostname or IP address>
Example:

shell
Copy code
tracert google.com
netstat
Displays network connections, routing tables, and a number of network interface statistics.

shell
Copy code
netstat
nslookup
Queries the DNS to obtain domain name or IP address mapping or any other specific DNS record.

shell
Copy code
nslookup <hostname>
Example:

shell
Copy code
nslookup google.com
Disk Management Commands
diskpart
Opens the Disk Partition command interpreter.

shell
Copy code
diskpart
format
Formats a disk for use with Windows.

shell
Copy code
format <volume> [options]
Example:

shell
Copy code
format D: /FS:NTFS
diskcopy
Copies the contents of one floppy disk to another.

shell
Copy code
diskcopy <drive1> <drive2>
Example:

shell
Copy code
diskcopy A: B:
User and Group Management Commands
net user
Adds, deletes, and displays user accounts.

shell
Copy code
net user [username [password | *] [options]] [/domain]
Example:

shell
Copy code
net user johndoe Pa$$w0rd /add
net localgroup
Adds, displays, or modifies local groups.

shell
Copy code
net localgroup [groupname [username [ ...]] [/add | /delete]]
Example:

shell
Copy code
net localgroup administrators johndoe /add
Miscellaneous Commands
cls
Clears the screen.

shell
Copy code
cls
echo
Displays messages, or turns command echoing on or off.

shell
Copy code
echo [message]
Example:

shell
Copy code
echo Hello, World!
pause
Suspends processing of a batch file and displays a message.

shell
Copy code
pause
shutdown
Shuts down or restarts the computer.

shell
Copy code
shutdown [options]
Example:

shell
Copy code
shutdown /s /t 0
type
Displays the contents of a text file.

shell
Copy code
type <filename>
Example:

shell
Copy code
type C:\example.txt
attrib
Displays or changes file attributes.

shell
Copy code
attrib [options] <filename>
Example:

shell
Copy code
attrib +r C:\example.txt
find
Searches for a text string in a file or files.

shell
Copy code
find "<string>" <filename>
Example:

shell
Copy code
find "Hello" C:\example.txt
fc
Compares two files and displays the differences.

shell
Copy code
fc <file1> <file2>
Example:

shell
Copy code
fc C:\file1.txt C:\file2.txt
replace
Replaces files.

shell
Copy code
replace <source> <destination> [options]
Example:

shell
Copy code
replace C:\newfile.txt D:\backup\
date
Displays or sets the date.

shell
Copy code
date [date]
Example:

shell
Copy code
date 12-31-2024
time
Displays or sets the system time.

shell
Copy code
time [time]
Example:

shell
Copy code
time 23:59
color
Sets the default console foreground and background colors.

shell
Copy code
color [attr]
Example:

shell
Copy code
color 0A
title
Sets the window title for the CMD session.

shell
Copy code
title [string]
Example:

shell
Copy code
title My Command Prompt
ver
Displays the Windows version.

shell
Copy code
ver
set
Displays, sets, or removes environment variables.

shell
Copy code
set [variable=[string]]
Example:

shell
Copy code
set PATH=C:\Windows\System32
