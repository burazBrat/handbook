# Linux Commands, Help & Tips

# Managing Packages

### Package manager

```
$ apt
```

### Package manager update

```
$ apt update
```

### Package manager upgrade

```
$ apt upgrade
```

### Install package

```
$ apt install package
```

### Remove package

```
$ apt remove package
```

# Navigating the File System


### Print working directory

```
$ pwd
```

### List directories

```
$ ls

$ ls -a

$ ls -l

$ ls -1 (eg, -1 directories level)
```

### Go in directory

```
$ cd directory_path
```

### Go in root directory

```
$ cd ~
```

# Manipulating Files and Directories


### Create directory

```
$ mkdir directory
```

### Rename directory

```
$ mv directory directory_new
```

### Create file

```
$ touch file.extension
```

### Remove file or directory

```
$ rm -r rile_or_directory
```

### Copying files

```
cp <source> <destination>
```

### Moving files

```
mv <source> <destination>
```

# Editing and Viewing Files

### Copy file content

```
$ cat file.extension
```

# Chaining Commands

### AND logic in commands (All or none)

```
$ command1 && command2 && command3
```

### Or logic in commands (Every true command will be executed)

```
$ command1 ; command2 ; command3
```

# Environment Variables


### Print env variables

```
$ printenv variable

$ echo $ variable
```

### Export command in terminal session

```
$ export variable=command
```

# Managing Processes


### Process list

```
$ ps
```

### Process kill

```
$ kill PROCESS_ID

$ kill -9 PROCESS_ID
```

### Find process by port

```
lsof -i :port
```

# Managing Users


### Command for file permissions 

```
$ chmod
```

### Chmod meaning

```
* 4 stands for "read"

* 2 stands for "write"

* 1 stands for "execute"

* 0 stands for "no permission."
```

### Chmod examples 

```
$ chmod 777 myfile
```


# CMD Shortcut

### Search

```
Ctrl + R
```

# CMD tips

### Command history

```
$ history
```





