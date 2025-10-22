# Linux File Permissions

Permissions in Linux determine who can read, write, or execute a file or folder. 
Understanding permissions is essential for working safely on any Linux system.

---

## Types of Permissions

Every file has three types of permissions:

1. Read (r) : Allows viewing the content.
2. Write (w) : Allows modifying the content.
3. Execute (x) : Allows running the file as a program.

Permissions are defined for three types of users:

1. Owner : The person who owns the file.
2. Group : Users who belong to the file's group.
3. Others : Everyone else.

Example: `rwxr-xr--` 
- Owner can read, write, and execute. 
- Group can read and execute. 
- Others can only read.


## Commands to Manage Permissions

- `ls -l` : Show the permissions of files in a directory.
- `chmod 755 file_name` : Change permissions of a file using numeric values.
- `chown user:group file_name` : Change the owner and group of a file.
- `chgrp group_name file_name` : Change only the group of a file.
