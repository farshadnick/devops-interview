# 1- service named X and it doesn’t work How do you Troubleshoot it ?
```
1- we need to check whether or not service is up  (netstat or systemctl status service-name)
2- Check Service log (journalctl or service’s log )
3- run commands that verify configuration 
 Like nginx -t (for nginx) 
4- check system’s resources like ram/cpu/disk usage
```

# 2-there is a nginx that is not working when you check the log it says your OS is running out of disk but when you check the disk you have 50 Gig free disk what’s the issue ?

```
The os Doesn't have free inod

```
# 3-What is ACL in linux?
```
ACLs provide a flexible and powerful mechanism for managing access control in Linux systems, 
enabling administrators to tailor permissions to specific users and groups according to the requirements of their environment

```
```
setfacl -m u:user:permissions /path/to/file_or_directory
getfacl  /path/to/file_or_directory
```

# 4-What is the difference between a process and a thread
```
A process is an independent program with its memory space,
while a thread is a lightweight process that shares the same memory space as other threads in the same process
```
