# AssignMent 1
## 50 Linux commands important for cloud and devops

## Name: Satyam R. Brahmankar    322071

### 1. ls
```sh
 ls 
```
It will show all file and folders in current directory.

### 2. mkdir

```sh
mkdir foldername
```
It will create folder in current directory

### 3. cd
```sh
cd foldername
```
This command helps to change the directory.

### 4.touch
```sh
touch filename
```
It us used to create a file.

### 5. nano
```sh
nano filename
```
Allows to write content in file & also can be used to create file

### 6. cat
```sh
cat filename
```
Used to display content of file.

### 7. rm
```sh
rm filename
```
Used to remove file.

```sh
rm *
```
Used to remove all files in current directory.

### 8. rmdir
```sh
rmdir -r foldername/
```
It will delete all content from folder recursively.

### 9. man (menual)
```sh
man command-ame
```
This will tell you everything (detail) about speciefied command.

### 10. cp (Copy)
```sh
cp filename foldername/
```
It will copy the file into specified folder.

### 11. mv (Move)
```sh
mv filename new_location/
```
Used to move files or directories to a new location.

### 12. pwd (Print Working Directory)
```sh
pwd
```
Displays the current working directory.

### 13. grep (Global Regular Expression Print)
```sh
grep "pattern" filename
```
Searches for a specific pattern in a file.

### 14. find
```sh
find /path/to/search -name "filename"
```
search for a file or directory in specified location

### 15.chmod (Change Mode)
```sh
chmod permissions filename
```
Changes the permissions of a file or directory.

### 16. chown (Change Owner)
```sh
chown user:group filename
```
Changes the owner and group of a file or directory.

### 17.wget
```sh
wget URL
```
Downloads files from the internet.

### 18. curl (Client for URLs)
```sh
curl -O URL
```
download files from the internet wih options for verious protocols

### 19. df (Disk Free)
```sh
df -h
```
display disk space usage

### 20. du (Disk Usage)
```sh
du path/file
```
shows the disk usage of files and directories

### 21.ps (Process Status)
```sh
ps aux
```
Displays information about active processes.

### 22. top
```sh
top
```
Displays real-time information about CPU and memory usage.

### 23.kill
```sh
kill process_id
```
terminates the process by its ID

### 24.systemctl
```sh
systemctl start/stop/restart service_name
```
Controls systemd services on Linux systems.

### 25.journalctl
```sh
journalctl -xe
```
Used to view the logs of the system.

### 26.ifconfig (Interface Configuration)
```sh
ifconfig
```
display network interface configuration.

### 27. ip
```sh
ip addr show
```
Displays information about network interfaces and routing tables.

### 28. ssh (Secure Shell)
```sh
ssh username@hostname
```
connect to remote machine securely.

### 29. scp (Secure Copy)
```sh
scp file username@hostname:/path/to/destination
```
Transfers files securely between hosts.

### 30. rsync (remote sync)
```sh
rsync -avz /path/to/source username@hostname:/path/to/destination
```
Synchronizes files and directories between hosts.

### 31. crontab (Cron Table)
```sh
crontab -e
```
Edits the crontable to scheduled task.

### 32.nc (Netcat)
```sh
nc -l -p port_number
```
Listens on a specified port for incoming connections.

### 33.lsof (List Open Files)
```sh
lsof -i :port_number
```
Lists open files and the processes that opened them, including network connections.

### 34.sudo (Superuser Do)
```sh
sudo command
```
Executes a command with superuser privileges.

### 35.uname (Unix Name)
```sh
uname -a
```
Displays system information such as kernel version and architecture.

### 36.hostname
```sh
hostname
```
display or sets the system's hostname

### 37.uptime
```sh
uptime
```
shows the how long system is running

### 38.who
```sh
who
```
Display information about user who is logged in

### 39.useradd
```sh
sudo useradd username
```
creates new user account

### 40.usermod
```sh
sudo usermod -aG groupname username
```
modifying the user account such as adding in a group

### 41.passwd
```sh
passwd
```
allows user to change their password

### 42.systemctl enable
```sh
systemctl enable service_name
```
Enable systemd service to start at boot

### 43.systemctl disable
```sh
systemctl disable service_name
```
Disables systemd service from start at boot.

### 44.systemctl status
```sh
systemctl status service_name
```
Displays the status of a systemd service.

### 45.journalctl

```sh
journalctl -u service_name
```
view logs of specific systemd service

### 46.git clone 
```sh
git clone repository_url
```
Clones the git repo

### 47.git pull
```sh
git pull
```
Updates the local repo with updated changes at remote repo

### 48.git push
```sh
git push
```
pushes the local changes to remote repo

### 49.git init
```sh
git init
```
initialize the git in local repo

### 50. docker 
```sh
docker run image_name
```
Runs a Docker container based on a specified image.
