# Cloud Security Lab 1: Linux Commands Study

## Introduction to Linux

**Linux** is an open-source operating system, and its kernel is the heart of the OS, facilitating communication between hardware and software. One of the key advantages of Linux is its customizability; developers can modify the Linux kernel to create their own tailored operating systems.

## Linux Commands

Linux commands are executed in the terminal, which is case-sensitive. This guide covers some basic and advanced commands used in Linux.

### 1. `ls` Command

The `ls` command is used to display a list of contents in a directory.

**Syntax:** 
```bash
ls
```

**Output:**

![ls](https://github.com/user-attachments/assets/b04ad6dc-276b-4b36-b167-fa3226374ad8)


### 2. `pwd` Command

The `pwd` command displays the location of the current working directory.

**Syntax:**
```bash
pwd
```

**Output:**

![pwd](https://github.com/user-attachments/assets/31508136-969e-4812-aaaf-e0d6241fe345)


### 3. `mkdir` Command

The `mkdir` command is used to create a new directory.

**Syntax:**
```bash
mkdir <directory_name>
```

**Output:**

![mkdir](https://github.com/user-attachments/assets/54af24c3-b808-4a79-958d-aac356daf425)


### 4. `rmdir` Command

The `rmdir` command is used to delete a directory.

**Syntax:**
```bash
rmdir <directory_name>
```

**Output:**

![rmdir](https://github.com/user-attachments/assets/6a10b1f9-1161-4806-a457-07c2cc979ed0)


### 5. `cd` Command

The `cd` command is used to change the current directory.

**Syntax:**
```bash
cd <directory_name>
```

**Output:**

![cd](https://github.com/user-attachments/assets/4bfb9aac-e9e7-40c3-b806-7ba5c38c704b)


### 6. `cat` Command

The `cat` command is used to create, display, and concatenate files.

**Syntax:**
```bash
cat [OPTION]... [FILE]...
```

**Output:**

![cat](https://github.com/user-attachments/assets/f82a2868-2cfa-43e6-93f0-2b6975e3ce7d)


### 7. `cp` Command

The `cp` command is used to copy files or directories.

**Syntax:**
```bash
cp <source_file> <destination_file>
```

**Output:**

![cat](https://github.com/user-attachments/assets/971f7404-a5bb-4153-8021-2ef5a6085b25)


## 8. `gedit` Command

`gedit` is a general-purpose text editor used to create and edit text files.

**Syntax:**
```bash
gedit <file_name>
gedit filename.txt 
```

### Output:
![gedit](https://github.com/user-attachments/assets/6ce379b4-d899-44df-8fbb-22a4d97e3249)


## 9. `su` Command

The `su` command provides administrative access to another user.

**Syntax:**
```bash
su <username>
su root
```

### Output:
![su](https://github.com/user-attachments/assets/d497e5ff-ef8c-47a4-8190-e9d97dd65755)


## 10. `mv` Command

The `mv` command is used to move a file or directory from one location to another.

**Syntax:**
```bash
mv <file_name> <directory_path>
mv filename.txt cloud2

```
### Output:
![mv](https://github.com/user-attachments/assets/220cc9f5-713f-4cb7-8cee-64390f80141b)


## 11. `rename` Command

The `rename` command is used to rename files.

**Syntax:**
```bash
rename oldfile.txt newfile.txt
```

### Output:


## 12. `head` Command

The `head` command displays the first 10 lines of a file.

**Syntax:**
```bash
head <file_name>
head filename.txt 
```

### Output:


## 13. `tail` Command

The `tail` command displays the last 10 lines of a file.

**Syntax:**
```bash
tail <file_name>
tail filename.txt 
```
### Output:


## 14. `id` Command

The `id` command displays the user ID (UID) and group ID (GID).

**Syntax:**
```bash
id
```

### Output:
![id](https://github.com/user-attachments/assets/c8f8007b-605f-4765-b772-36ba779bb1f8)


### 15. `grep` Command

The `grep` command is used to search for a pattern within files.

**Syntax:**
```bash
command | grep <search_word>
```

### Output:
![grep](https://github.com/user-attachments/assets/eaf14288-3a77-41e7-bc96-4e5142975b2d)


## 16. `tr` Command

The `tr` command is used to translate or delete characters.

**Syntax:**
```bash
command | tr <old> <new>
echo "hello world" | tr 'a-z' 'A-Z'
echo "banana" | tr -d 'a'
echo "one two three" | tr ' ' '\n'
```

### Output:
![tr](https://github.com/user-attachments/assets/21253ce7-3ac7-4f99-b829-a7d72bf25f3a)


## 17. `chmod` Command

The `chmod` command is used to change the access mode (permissions) of a file.

**Syntax:**
```bash
chmod <options> <permissions> <file_name>
chmod 755 file1
```

### Output:
![chmod](https://github.com/user-attachments/assets/846a6072-a7c8-453d-bb65-33fc5cb0ffe0)


## 18. `tar` Command

The `tar` command is used to create or extract archive files.

**Syntax:**
```bash
tar [options] [archive-file] [files_to_archive]
tar -cvf archive.tar file1 file2
```

### Output:

## 19. `chown` Command

The `chown` command is used to change the ownership of a file.

**Syntax:**
```bash
chown <owner_name> <file_name>
chown bharathi:root file1
```

### Output:

## 20. `make` Command

The `make` command is used to build and maintain groups of programs.

**Syntax:**
```bash
make [-f makefile] [options] [targets]
nano Makefile
make
make clean
```

### Output:

## 21. `ifconfig` Command

The `ifconfig` command is used to configure network interfaces.

**Syntax:**
```bash
ifconfig [options] [interface]
```

### Output:
![ifconfig](https://github.com/user-attachments/assets/207690a3-4b0b-417d-9a5e-7cb52d180cbe)


## 22. `chmod 777` Command

The `chmod 777` command gives read, write, and execute permissions to the owner, group, and others.

**Syntax:**
```bash
chmod 777 <file_name>
chmod 777 filename.txt 
```

### Output:
![chmod](https://github.com/user-attachments/assets/cbcd8c5f-3858-48db-986d-4091aa0ad10f)


## 23. `host` Command

The `host` command is used to display the IP address for a given domain name.

**Syntax:**
```bash
host <domain_name> or <ip_address>
host www.amazon.com

```

### Output:
![host](https://github.com/user-attachments/assets/43e84164-2be6-44c3-8406-c907b19e06bb)


## 24. `gzip` Command

The `gzip` command is used to compress files, replacing the original file with a compressed one with a `.gz` extension.

**Syntax:**
```bash
gzip filename.txt
gzip -d filename.txt.gz
gzip -k filename.txt
gzip -l filename.txt.gz  
```

### Output:
![gzip](https://github.com/user-attachments/assets/267d407f-9544-4e48-963f-291d06bf28a2)


## 25. `sort` Command

The `sort` command is used to sort the contents of a file alphabetically.

**Syntax:**
```bash
sort <file_name>
sort filename.txt
```

### Output:
![sort](https://github.com/user-attachments/assets/113b4132-4a6d-4461-a1a5-389da851f2e5)


## 26. `cal` Command

The `cal` command displays the current month's calendar with the current date highlighted.

**Syntax:**
```bash
cal
```

### Output:
![cal](https://github.com/user-attachments/assets/cce85aa7-c376-45f5-948b-c8b3d901ece7)


## 27. `clear` Command

The `clear` command clears the terminal screen.

**Syntax:**
```bash
clear
```

### Output:
![clear](https://github.com/user-attachments/assets/e8171fc2-64de-494c-94fc-1eb6af19883f)


## 28. `mail` Command

The `mail` command is used to send emails from the command line.

**Syntax:**
```bash
mail
```

### Output:

## 29. `df` Command

The `df` command displays the disk space usage of file systems.

**Syntax:**
```bash
df
```

### Output:
![df](https://github.com/user-attachments/assets/5733af36-274d-41f0-b794-9c972f810a4a)


## 30. `find` Command

The `find` command is used to search for files in a directory hierarchy.

**Syntax:**
```bash
find <directory> -name <file_name>
find /etc -name "passwd"
```

### Output:
![find](https://github.com/user-attachments/assets/1db41b64-197e-471b-aace-8fb18cf0046b)


## Result :
Linux commands are executed in the linux terminal successfully.
