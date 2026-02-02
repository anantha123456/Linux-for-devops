### Basic Linux Commands

# | Command        | Description                   |

- | pwd            | Shows current directory path  |
- | ls             | Lists files and folders       |
- | cd             | Change directory              |
- | mkdir          | Create new directory          |
- | rmdir          | Remove directory              |
- | touch          | Create empty file             |
- | cp             | Copy files                    |
- | mv             | Move or rename files          |
- | rm             | Delete files                  |
- | cat            | View file content             |
- | head , tail    | View first/last lines of file |
- | man            | Display manual page           |
- | clear          | Clear terminal screen         |
- | history        | View previously used commands |


### Linux File System Structure

# | Directory  | Description                          |

- | /          | Root directory                       |
- | /bin       | Essential user commands (ls, cp, mv) |
- | /boot      | Boot loader files                    |
- | /dev       | Device files                         |
- | /etc       | Configuration files                  |
- | /home      | Home directories for users           |
- | /lib       | Shared libraries                     |
- | /media     | External drives                      |
- | /mnt       | Mounted devices                      |
- | /opt       | Optional software packages           |
- | /root      | Root user home directory             |
- | /tmp       | Temporary files                      |
- | /usr       | User programs                        |
- | /var       | Log files, spool files               |


### User Management

# | Command                        | Description           |

- | whoami                         | Shows current user    |
- | adduser username               | Create new user       |
- | passwd username                | Set/change password   |
- | su username                    | Switch user           |
- | userdel username               | Delete user           |
- | groupadd groupname             | Create new group      |
- | usermod -aG groupname username | Add user to a group   |
- | id username                    | Check user’s UID, GID |


### File Permissions

Each file has three permission types:

r = Read (4)
w = Write (2)
x = Execute (1)

Permission Levels:

Owner
Group
Others

Example: -rwxr-xr--

Owner: rwx → 7
Group: r-x → 5
Others: r-- → 4

So → chmod 754 filename

# | Command | Description            |

- | chmod   | Change permissions     |
- | chown   | Change ownership       |
- | chgrp   | Change group ownership |


### File Compression & Archiving

# | Command                       | Description      |

- | tar -cvf backup.tar /folder   | Create archive   |
- | tar -xvf backup.tar           | Extract archive  |
- | gzip filename                 | Compress file    |
- | gunzip filename.gz            | Decompress file  |
- | zip -r file.zip /folder       | Create zip file  |
- | unzip file.zip                | Extract zip file |


### Process Management

# | Command               | Description               |

- | ps                    | Show active processes     |
- | top                   | Display running processes |
- | kill PID              | Terminate a process       |
- | killall processname   | Kill all instances        |
- | nice , renice         | Adjust process priority   |
- | df -h                 | Show disk usage           |
- | du -sh folder         | Show folder size          |
- | free -h               | Show memory usage         |


### Networking Commands

# | Command                  | Description               |

- | ifconfig                 | Show IP info (old)        |
- | ip addr show             | Show IP info (new)        |
- | ping google.com          | Test network connectivity |
- | netstat -tuln            | Show active connections   |
- | ss -tuln                 | Show socket connections   |
- | hostname                 | Display system hostname   |
- | nslookup domain          | DNS lookup                |
- | scp file user@ip:/path   | Secure file copy          |
- | ssh user@ip              | Connect to remote system  |


### Package Management

- Debian/Ubuntu:
apt update
apt install package-name
apt remove package-name

- RHEL/CentOS:
yum update
yum install package-name
yum remove package-name


### Shell & Shell Scripting

Shell = Command interpreter between user & kernel.
Types of Shell:
bash (Bourne Again Shell) — Most common
sh, csh, ksh, zsh

### Scheduling Tasks

# | Command      | Description    |

- | crontab -e   | Edit cron jobs |
- | crontab -l   | List cron jobs |


### System Logs

# | Location            | Description             |

- | /var/log/syslog     | System logs             |
- | /var/log/auth.log   | Authentication logs     |
- | /var/log/messages   | General system messages |
- | /var/log/boot.log   | Boot messages           |


### Disk Management

# | Command                | Description          |

- | df -h                  | Show disk space      |
- | du -sh                 | Show directory size  |
- | fdisk -l               | List disk partitions |
- | mount /dev/sdb1 /mnt   | Mount disk           |
- | umount /mnt            | Unmount disk         |


### Environment Variables

# | Command            | Description                |

- | printenv           | Show environment variables |
- | echo $PATH         | Show PATH variable         |
- | export VAR=value   | Set new variable           |


### Linux for DevOps

# Linux is the backbone of DevOps.

we will use Linux for:
Deploying apps on servers
Writing automation scripts
Running Docker & Kubernetes
Managing CI/CD pipelines
Monitoring systems











