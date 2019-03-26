### Log into local & remote graphical and text mode consoles

Login to a remote server with the user user
```
ssh user@server 
or
ssh -l user server
```

### Search for files

Find all files with SUID
```
find / -perm -4000 
or
find / -perm /4000
```
Find all files with GUID
```
find / -perm -2000
or
find / -perm /2000
```


Find all files with sticky bit
```
find / -perm -1000
or
find / -perm /1000
```

Find all files which are links
```
find / -type l
```

Find all files which are directories
```
find / -type d
```
Find all files which are files
```
find / -type f
```

Find all files that are of extension .doc and add them to a tarball
```
find / -name "*.doc" -exec tar -rvf out.tar {} + 2>/dev/null
```


Evaluate and compare the basic file system features and options
Compare and manipulate file content
Use input-output redirection (e.g. >, >>, |, 2>)
Analyze text using basic regular expressions
Archive, backup, compress, unpack, and uncompress files
Create, delete, copy, and move files and directories
Create and manage hard and soft links
List, set, and change standard file permissions
Read, and use system documentation
Manage access to the root account

