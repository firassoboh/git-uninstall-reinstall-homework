
# File Manipulation Commands Assignment




### pwd (Print Working Directory)

```bash
user@kalii:~\$ pwd
/home/user
```

### ls (List)

```bash

user@kalii:~\$ ls -lah
total 24K
drwxr-xr-x  3 user user 4.0K Oct 11 19:45 .
drwxr-xr-x  3 root root 4.0K Oct 11 19:40 ..
-rw-r--r--  1 user user  220 Oct 11 19:40 .bash_logout
-rw-r--r--  1 user user 3.7K Oct 11 19:40 .bashrc
-rw-r--r--  1 user user  807 Oct 11 19:40 .profile
drwxr-xr-x 2 user user 4.0K Oct 11 19:45 .git
```

### tree

```bash

user@kalii:~\$ tree -L 2 -a
.
├── .bash_logout
├── .bashrc
├── file1.txt
├── file2.txt
├── notes.log
└── project
    └── src
```

---



### mkdir (Make Directory)

```bash

user@kalii:~\$ mkdir -p project/src/assets
```

### touch

```bash

user@kalii:~\$ touch file1.txt file2.txt notes.log
```

### nano

```bash

user@kalii:~\$ nano file1.txt

```

---



### cat (Concatenate)

```bash

user@kalii:~\$ cat -n file1.txt
     1	Hello World!
     2	This is a line inside file1.txt.
```

### head

```bash

user@kalii:~\$ head -n 2 notes.log
[2026-10-11 19:45:01] System started.
[2026-10-11 19:45:05] User logged in.
```

### tail

```bash

user@kalii:~\$ tail -n 1 notes.log
[2026-10-11 19:46:12] Service execution completed.
```

### less

```bash

user@kalii:~\$ less -N notes.log

```

---



### rm (Remove)

```bash

user@kalii:~\$ rm -rf project/
```

### rmdir (Remove Empty Directories)

```bash

user@kalii:~\$ mkdir -p empty_dir/src
user@kalii:~\$ rmdir -p empty_dir/src
```
user@kalii:~\$ rmdir -p empty_dir/src
```
