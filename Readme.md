### Core Components of Linux

# Kernel:
The heart of the OS — managescommunication between software and hardware.

# Shell:
Interface that lets users interact with the OS.
CLI (Command Line Interface): Text-based commands
GUI (Graphical User Interface): Visual interface

# Command:
Instruction given by the user to perform a specific task.

# Terminal:
A text-based interface used to execute commands and communicate with the system.


### User Access in Linux

Default user: ec2-user
Root user: Full permissions (superuser)
To switch to root: [sudo -i or sudo su -]
To exit root: exit

## Types of Linux Commands

-System Commands
-Hardware Commands
-File Commands
-Permission Commands
-User Commands
-Search Commands
-Networking Commands

## System Commands

# | Command   |        | Description|
- |uname        |      | Get OS type|
- |uname -r     |      | Kernel version|
- |uname -a     |      | Full system info|
- |clear/ Ctrl+ L|     | Clear terminal|
- |uptime       |      | System running time|
- |hostname     |      | Private DNS name|
- |hostname -i  |      | Private IP|
- |ip addr / ifconfig || Get IP details|
- |date         |      | Display current date|
- |timedatectl  |      | Show time zones|
- |who          |      | Show logged-in users|
- |whoami       |      | Show current user|

## Hardware Commands

# |Command    |    | Description|
- |lscpu      |    | CPU information|
- |top        |    | CPU utilization|
- |df -h      |    | Disk space usage|
- |free       |    | Free RAM info|
- |free -m    |    | RAM in MB|
- |free -h    |    | Human-readable format|

## File Commands

# |Command            |    | Description|
- |touch filename     |    | Create file|
- |touch aws azure gcp|    | Create multiple files|
- |touch linux{1..5}  |    | Create files linux1 to linux5|
- |rm filename        |    | Remove file|
- |rm -f filename     |    | Force remove file|
- |rm -f *            |    | Delete all files|
- |rm -f *.txt        |    | Delete all .txt files|
- |rm -f a*           |    | Delete files starting with ‘a’|

## Folder Commands

# |Command                 |   |Description|
- |mkdir foldername        |   | Create folder|
- |mkdir git maven jenkins |   |Create multiple folders|
- |mkdir docker{1..5}      |   |Create 5 folders|
- |rmdir foldername        |   |Remove empty folder|
- |rm -rf *                |   |Remove all files & folders (including non-empty)|

## List Files & Folders

# |Command    |     | Description |
- |ls         |     | List files/folders (names only)|
- |ll         |     | Detailed list with permissions & metadata|

## Change Directory

# |Command       |   | Description |
- |cd foldername |   | Go inside folder|
- |cd            |   | Go to home directory|
- |cd -          |   | Go to previous directory|
- |cd ../        |   | Move one folder back|
- |cd ../../     |   | Move two folders back

## Directory Management

# |Command                    |   | Description|
- |mkdir folder1/folder2      |   | Create nested folders|
- |ll folder1                 |   | View files inside folder1|
- |touch folder1/aws.txt      |   | Create file inside folder|
- |mkdir -p aws/azure/gcp/ccit|   | Create parent-child folders automatically|


### Pro tips

- Press Tab to auto-complete file/folder names
- Use ↑ (up arrow) to get previous commands
- Press Ctrl + U to clear the entire line
- Ctrl + E → Move to end of command
- Ctrl + A → Move to beginning of command
