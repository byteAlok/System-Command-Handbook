# 📘 Linux Command Handbook

Essential Linux Commands for Software Engineers • DevOps • Cloud • Software Architects

## 📦 Chunk 1 (Commands 1–50)
### Linux Fundamentals

### 📂 Category 1: Navigation & Paths (Commands 1–8)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 1 | `pwd` | Displays absolute path of current working directory. | `pwd` |
| 2 | `ls` | Lists files and directories in current location. | `ls` |
| 3 | `ls -l` | Lists files with detailed information and permissions. | `ls -l` |
| 4 | `ls -la` | Lists all files including hidden ones. | `ls -la` |
| 5 | `cd` | Changes current directory to specified destination path. | `cd /home/user` |
| 6 | `cd ..` | Moves one directory level above current location. | `cd ..` |
| 7 | `cd -` | Switches directly to current user's home directory. | `cd -` |
| 8 | `tree` | Displays directory structure in hierarchical tree format. | `tree` |

### 📁 Category 2: Files & Directories (Commands 9–22)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 9 | `mkdir` | Creates one or multiple new directories. | `mkdir project` |
| 10 | `mkdir -p` | Creates nested directories without intermediate errors. | `mkdir -p app/src` |
| 11 | `rmdir` | Removes empty directory from the filesystem safely. | `rmdir temp` |
| 12 | `touch` | Creates empty file or updates file timestamp. | `touch index.html` |
| 13 | `cp` | Copies files or directories to another location. | `cp file.txt backup/` |
| 14 | `cp -r` | Copies directories recursively with all contents included. | `cp -r app backup` |
| 15 | `mv` | Moves or renames files and directories efficiently. | `mv old.txt new.txt` |
| 16 | `rm` | Permanently removes files from the filesystem. | `rm notes.txt` |
| 17 | `rm -r` | Recursively removes directories and their contents. | `rm -r temp` |
| 18 | `rm -rf` | Forcefully removes directories without confirmation prompts. | `rm -rf build` |
| 19 | `ln` | Creates hard links between filesystem objects. | `ln file.txt link.txt` |
| 20 | `ln -s` | Creates symbolic links pointing to target files. | `ln -s app shortcut` |
| 21 | `stat` | Displays detailed metadata about specified filesystem objects. | `stat app.log` |
| 22 | `file` | Identifies actual file type using content analysis. | `file image.png` |

### 📄 Category 3: Viewing Files (Commands 23–30)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 23 | `cat` | Displays complete contents of specified text files. | `cat notes.txt` |
| 24 | `less` | Views large files interactively one page at time. | `less app.log` |
| 25 | `more` | Displays file contents one screen at time. | `more data.txt` |
| 26 | `head` | Displays first ten lines of specified file. | `head app.log` |
| 27 | `head -n` | Displays specified number of initial file lines. | `head -20 app.log` |
| 28 | `tail` | Displays last ten lines of specified file. | `tail app.log` |
| 29 | `tail -f` | Continuously monitors appended data in log files. | `tail -f nginx.log` |
| 30 | `nl` | Displays file contents with line numbers included. | `nl notes.txt` |

### 🔍 Category 4: Searching & Text Processing (Commands 31–45)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 31 | `find` | Searches files and directories using specified search criteria. | `find . -name "*.log"` |
| 32 | `locate` | Quickly finds files using indexed system database. | `locate nginx.conf` |
| 33 | `grep` | Searches matching text patterns within files efficiently. | `grep "error" app.log` |
| 34 | `grep -r` | Recursively searches matching text inside directories. | `grep -r "TODO" src/` |
| 35 | `awk` | Processes structured text using pattern-action programming. | `awk '{print $1}' file.txt` |
| 36 | `sed` | Edits and transforms text streams automatically. | `sed 's/old/new/g' file.txt` |
| 37 | `sort` | Sorts text lines alphabetically or numerically ascending. | `sort names.txt` |
| 38 | `uniq` | Removes adjacent duplicate lines from sorted output. | `sort file.txt \| uniq` |
| 39 | `cut` | Extracts selected columns or character ranges efficiently. | `cut -d: -f1 /etc/passwd` |
| 40 | `tr` | Translates or deletes specified input characters. | `echo "abc" \| tr a-z A-Z` |
| 41 | `wc` | Counts lines, words, characters, and bytes accurately. | `wc -l app.log` |
| 42 | `tee` | Writes command output to file and terminal. | `ls \| tee files.txt` |
| 43 | `xargs` | Builds command arguments from standard input stream. | `find . -name "*.log" \| xargs rm` |
| 44 | `diff` | Compares two files and shows line differences. | `diff old.txt new.txt` |
| 45 | `paste` | Merges corresponding lines from multiple input files. | `paste file1.txt file2.txt` |

### 📖 Category 5: Help & Documentation (Commands 46–50)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 46 | `man` | Displays complete manual page for specified command. | `man grep` |
| 47 | `--help` | Shows quick command usage and available options. | `ls --help` |
| 48 | `which` | Displays executable location found in system PATH. | `which python3` |
| 49 | `whereis` | Locates binary, source, and manual page files. | `whereis ssh` |
| 50 | `history` | Displays previously executed terminal commands chronologically. | `history` |

> **Chunk 1 Complete (Commands 1–50)**
> Covered Categories:
> - 📂 Navigation & Paths (1–8)
> - 📁 Files & Directories (9–22)
> - 📄 Viewing Files (23–30)
> - 🔍 Searching & Text Processing (31–45)
> - 📖 Help & Documentation (46–50)

## 📦 Chunk 2 (Commands 51–100)
### Linux Administration

### 🔐 Category 6: File Permissions & Ownership (Commands 51–60)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 51 | `chmod` | Changes file or directory access permissions securely. | `chmod 755 script.sh` |
| 52 | `chmod +x` | Grants executable permission to specified file. | `chmod +x deploy.sh` |
| 53 | `chmod -R` | Recursively changes permissions for entire directory. | `chmod -R 755 project/` |
| 54 | `chown` | Changes file or directory ownership to user. | `chown ubuntu app.log` |
| 55 | `chown -R` | Recursively changes ownership of directory contents. | `chown -R nginx:nginx /var/www` |
| 56 | `chgrp` | Changes group ownership of specified files. | `chgrp developers app.log` |
| 57 | `umask` | Sets default permissions for newly created files. | `umask 022` |
| 58 | `getfacl` | Displays Access Control Lists for files. | `getfacl app.log` |
| 59 | `setfacl` | Configures Access Control Lists on files. | `setfacl -m u:john:rwx file.txt` |
| 60 | `ls -l` | Displays permissions, ownership, and detailed file information. | `ls -l` |

### 👤 Category 7: User & Group Management (Commands 61–75)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 61 | `whoami` | Displays username of currently logged-in user. | `whoami` |
| 62 | `id` | Displays user ID and group memberships. | `id` |
| 63 | `who` | Lists users currently logged into system. | `who` |
| 64 | `groups` | Displays groups associated with current user. | `groups` |
| 65 | `useradd` | Creates a new user account securely. | `sudo useradd alok` |
| 66 | `adduser` | Creates user account with interactive prompts. | `sudo adduser alok` |
| 67 | `passwd` | Sets or changes user account password. | `passwd alok` |
| 68 | `usermod` | Modifies existing user account properties safely. | `usermod -aG sudo alok` |
| 69 | `userdel` | Deletes user account from the system. | `userdel alok` |
| 70 | `groupadd` | Creates a new user group. | `groupadd developers` |
| 71 | `groupmod` | Modifies existing user group properties. | `groupmod developers` |
| 72 | `groupdel` | Deletes an existing user group. | `groupdel developers` |
| 73 | `su` | Switches current session to another user. | `su root` |
| 74 | `sudo` | Executes commands with administrative privileges safely. | `sudo apt update` |
| 75 | `visudo` | Safely edits sudoers configuration without syntax errors. | `sudo visudo` |

### ⚙️ Category 8: Process Management (Commands 76–90)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 76 | `ps` | Displays currently running processes with details. | `ps` |
| 77 | `ps -ef` | Displays all running system processes comprehensively. | `ps -ef` |
| 78 | `top` | Monitors running processes and resource usage live. | `top` |
| 79 | `htop` | Provides interactive real-time process management interface. | `htop` |
| 80 | `kill` | Terminates process using specified process identifier. | `kill 1234` |
| 81 | `kill -9` | Forcefully terminates unresponsive running process immediately. | `kill -9 1234` |
| 82 | `pkill` | Terminates processes matching specified process name. | `pkill nginx` |
| 83 | `killall` | Terminates all processes with matching name. | `killall chrome` |
| 84 | `jobs` | Lists background jobs in current shell session. | `jobs` |
| 85 | `bg` | Resumes stopped job execution in background. | `bg %1` |
| 86 | `fg` | Brings background job into foreground execution. | `fg %1` |
| 87 | `nohup` | Keeps process running after terminal logout. | `nohup java -jar app.jar &` |
| 88 | `nice` | Starts process with adjusted CPU priority. | `nice -10 script.sh` |
| 89 | `renice` | Changes CPU priority of running processes. | `renice 5 1234` |
| 90 | `pidof` | Displays process identifier for specified program. | `pidof nginx` |

### 💻 Category 9: System Information (Commands 91–100)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 91 | `uname` | Displays basic operating system kernel information. | `uname -a` |
| 92 | `hostname` | Displays current system hostname or network name. | `hostname` |
| 93 | `hostnamectl` | Displays or modifies system hostname configuration. | `hostnamectl` |
| 94 | `uptime` | Shows system running duration and load averages. | `uptime` |
| 95 | `date` | Displays or sets current system date. | `date` |
| 96 | `cal` | Displays calendar for specified month or year. | `cal` |
| 97 | `free` | Displays system memory and swap usage. | `free -h` |
| 98 | `lscpu` | Displays detailed processor architecture and information. | `lscpu` |
| 99 | `lsmem` | Displays installed physical memory layout information. | `lsmem` |
| 100 | `env` | Displays all current environment variables available. | `env` |

> **Chunk 2 Complete (Commands 51–100)**
> Covered Categories:
> - 🔐 File Permissions & Ownership (51–60)
> - 👤 User & Group Management (61–75)
> - ⚙️ Process Management (76–90)
> - 💻 System Information (91–100)

## 📦 Chunk 3 (Commands 101–150)
### Server Administration

### 💾 Category 10: Disk & Storage Management (Commands 101–112)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 101 | `df` | Displays filesystem disk space usage statistics. | `df -h` |
| 102 | `du` | Displays disk usage for files and directories. | `du -sh project/` |
| 103 | `lsblk` | Lists available block storage devices and partitions. | `lsblk` |
| 104 | `blkid` | Displays filesystem UUIDs and partition information. | `sudo blkid` |
| 105 | `fdisk` | Creates, deletes, and manages disk partitions. | `sudo fdisk /dev/sda` |
| 106 | `mount` | Mounts filesystem to specified directory location. | `sudo mount /dev/sdb1 /mnt` |
| 107 | `umount` | Safely unmounts mounted filesystem from directory. | `sudo umount /mnt` |
| 108 | `mkfs` | Creates filesystem on specified storage partition. | `sudo mkfs.ext4 /dev/sdb1` |
| 109 | `fsck` | Checks and repairs filesystem consistency errors. | `sudo fsck /dev/sdb1` |
| 110 | `sync` | Flushes filesystem buffers to physical storage safely. | `sync` |
| 111 | `dd` | Copies and converts files or disk images. | `dd if=/dev/sda of=backup.img` |
| 112 | `mountpoint` | Checks whether directory is mounted filesystem. | `mountpoint /mnt` |

### 🌐 Category 11: Networking (Commands 113–132)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 113 | `ip` | Configures and displays network interface information. | `ip addr` |
| 114 | `ping` | Tests network connectivity with remote host. | `ping google.com` |
| 115 | `traceroute` | Displays network path packets travel through. | `traceroute google.com` |
| 116 | `tracepath` | Traces packet route without administrative privileges. | `tracepath google.com` |
| 117 | `ss` | Displays active network sockets and connections. | `ss -tuln` |
| 118 | `netstat` | Displays network connections, routes, and statistics. | `netstat -tuln` |
| 119 | `curl` | Transfers data from or to remote servers. | `curl https://example.com` |
| 120 | `wget` | Downloads files directly from internet servers. | `wget https://example.com/file.zip` |
| 121 | `scp` | Securely copies files between remote systems. | `scp file.txt user@host:/home/user` |
| 122 | `rsync` | Efficiently synchronizes files between local or remote systems. | `rsync -av src/ backup/` |
| 123 | `ssh` | Securely connects to remote Linux servers. | `ssh user@server` |
| 124 | `sftp` | Securely transfers files using SSH protocol. | `sftp user@server` |
| 125 | `dig` | Queries DNS servers for domain information. | `dig google.com` |
| 126 | `nslookup` | Looks up domain names and IP addresses. | `nslookup google.com` |
| 127 | `host` | Resolves hostnames into corresponding IP addresses. | `host google.com` |
| 128 | `hostname -I` | Displays all assigned local IP addresses. | `hostname -I` |
| 129 | `arp` | Displays and manages Address Resolution Protocol cache. | `arp -a` |
| 130 | `route` | Displays or modifies kernel routing table. | `route -n` |
| 131 | `nc` | Tests network ports and transfers raw data. | `nc -zv localhost 80` |
| 132 | `telnet` | Connects to remote services for connectivity testing. | `telnet localhost 80` |

### 📦 Category 12: Package Management (Commands 133–140)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 133 | `apt` | Installs, removes, and manages Debian packages. | `sudo apt install nginx` |
| 134 | `apt update` | Updates package repository metadata from servers. | `sudo apt update` |
| 135 | `apt upgrade` | Upgrades installed packages to latest versions. | `sudo apt upgrade` |
| 136 | `apt remove` | Removes installed package while preserving configuration. | `sudo apt remove nginx` |
| 137 | `apt purge` | Completely removes package including configuration files. | `sudo apt purge nginx` |
| 138 | `dpkg` | Installs or manages local Debian package files. | `sudo dpkg -i app.deb` |
| 139 | `yum` | Manages packages on RHEL and CentOS systems. | `sudo yum install httpd` |
| 140 | `dnf` | Modern package manager replacing yum on Fedora. | `sudo dnf install nginx` |

### 📜 Category 13: Services & Log Management (Commands 141–150)

| # | Command | Short Definition (6–10 words) | Example |
|---|---|---|---|
| 141 | `systemctl` | Manages system services and startup behavior. | `systemctl status nginx` |
| 142 | `systemctl start` | Starts specified service immediately on system. | `sudo systemctl start nginx` |
| 143 | `systemctl stop` | Stops specified running service safely. | `sudo systemctl stop nginx` |
| 144 | `systemctl restart` | Restarts specified service to apply changes. | `sudo systemctl restart nginx` |
| 145 | `systemctl enable` | Enables service to start during boot. | `sudo systemctl enable nginx` |
| 146 | `systemctl disable` | Prevents service from starting during boot. | `sudo systemctl disable nginx` |
| 147 | `journalctl` | Displays logs collected by systemd journal service. | `journalctl -u nginx` |
| 148 | `dmesg` | Displays Linux kernel boot and hardware messages. | `dmesg` |
| 149 | `watch` | Repeatedly executes command and refreshes output. | `watch -n 2 ls` |
| 150 | `crontab` | Schedules commands to run at specific times. | `crontab -e` |

> **Chunk 3 Complete (Commands 101–150)**
> Covered Categories:
> - 💾 Disk & Storage Management (101–112)
> - 🌐 Networking (113–132)
> - 📦 Package Management (133–140)
> - 📜 Services & Log Management (141–150)
