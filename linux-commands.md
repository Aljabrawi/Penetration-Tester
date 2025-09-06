# Linux Basic Commands 

This file contains basic Linux commands with explanations and examples.

---

## 1. pwd – Print Working Directory
Shows the current directory you are in.

**Example 1:**
```bash
$ pwd
/home/mohammed

**Example 2:**
$ cd Documents
$ pwd
/home/mohammed/Documents

## 2. ls – List Files and Directories
Lists files and folders in the current directory. Use flags like -l for details or -a to show hidden files.
**Example 1:**
$ ls
Documents  Downloads  Pictures

**Example 2:**
$ ls -la
drwxr-xr-x 2 mohammed mohammed 4096 Sep 6 16:00 .


## 3. cd – Change Directory
Move between directories

**Example 1:**
$ cd Downloads
$ pwd
/home/mohammed/Downloads

**Example 2:**
$ cd ..
$ pwd
/home/mohammed


## 4. mkdir – Make Directory
Create a new folder.

**Example 1:**
$ mkdir my-lab
$ ls
my-lab

**Example 2:**
$ mkdir -p labs/network
$ ls labs
network


## 5. touch – Create Empty File
Quickly create a new empty file

**Example 1:**
$ touch notes.txt
$ ls
notes.txt

**Example 2:**
$ touch lab1.txt lab2.txt
$ ls
lab1.txt  lab2.txt


## 6. rm – Remove File or Directory
Delete files or folders. Use -r for directories.

**Example 1:**
$ rm notes.txt

**Example 2:**
$ rm -r my-lab


## 7. mv – Move or Rename File/Directory
Move a file or rename it.

**Example 1:**
$ mv lab1.txt Documents/

**Example 2:**
$ mv oldname.txt newname.txt


## 8. nano – Edit or Create File
Open the nano text editor to edit or create files.

**Example 1:**
$ nano notes.txt
(Press CTRL+O to save, CTRL+X to exit)

**Example 2:**
$ nano lab1.md

## 9. echo – Print Text or Write to File
Prints text to terminal or file.

**Example 1:**
$ echo "Hello World"
Hello World

**Example 2:**
$ echo "This is a note" > notes.txt
$ cat notes.txt
This is a note

## 10. cp – Copy File or Directory
Copy files or folders. Use -r for directories.

**Example 1:**
$ cp notes.txt backup-notes.txt

**Example 2:**
$ cp -r labs labs-backup

## 11. cat – View File Content
Display the content of a file.

**Example 1:**
$ cat notes.txt
This is a note.

**Example 2:**
$ cat lab1.md
# Lab 1 - Network Basics


## 12. head – View Start of File
Show the first lines of a file.

**Example 1:**
$ head notes.txt
This is a note.

**Example 2:**
$ head -n 5 lab1.md

## 13. tail – View End of File
Show the last lines of a file.

**Example 1:**
$ tail notes.txt
This is a note.

**Example 2:**
$ tail -n 10 lab1.md


## 14. find – Find Files and Directories
Search for files or folders by name.

**Example 1:**
$ find /home/mohammed -name "*.txt"

**Example 2:**
$ find . -type d -name "labs"


## 15. less – View File Page by Page
View large files page by page.

**Example 1:**
$ less lab1.md
(Use space to scroll, q to quit)

**Example 2:**
$ less /var/log/syslog

## 16. sudo – Run Command as Root
Execute commands with superuser privileges.

**Example 1:**
$ sudo apt update


**Example 2:**
$ sudo mkdir /opt/newfolder

## 17.

$ sudo adduser mohammed
$ sudo usermod -aG sudo mohammed
$ sudo deluser --remove-home mohammed


These are the most basic Linux commands for beginners with examples.
Keep practicing each one by typing them in your terminal.

