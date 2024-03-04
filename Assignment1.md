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

###12. pwd (Print Working Directory)
```sh
pwd
```
Displays the current working directory.

###13. grep (Global Regular Expression Print)
```sh
grep "pattern" filename
```
Searches for a specific pattern in a file.

###14. find
```sh
find /path/to/search -name "filename"
```
search for a file or directory in specified location

###15.chmod (Change Mode)
```sh
chmod permissions filename
```
Changes the permissions of a file or directory.

###16. chown (Change Owner)
```sh
chown user:group filename
```
Changes the owner and group of a file or directory.

###17.wget
```sh
wget URL
```
Downloads files from the internet.

###18. curl (Client for URLs)
```sh
curl -O URL
```
download files from the internet wih options for verious protocols

###19. df (Disk Free)
```sh
df -h
```
display disk space usage

###20. du (Disk Usage)
```sh
du path/file
```
shows the disk usage of files and directories

###21.ps (Process Status)
```sh
ps aux
```
Displays information about active processes.

###22. top
```sh
top
```
Displays real-time information about CPU and memory usage.

###23.kill
```sh
kill process_id
```
terminates the process by its ID

###24.systemctl
```sh
systemctl start/stop/restart service_name
```
Controls systemd services on Linux systems.

###25.journalctl
```sh
journalctl -xe
```
Used to view the logs of the system.

###26.ifconfig (Interface Configuration)
```sh
ifconfig
```
display network interface configuration.
