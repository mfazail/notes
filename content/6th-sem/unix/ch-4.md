# CH 4

1. **File and Directory Attributes**:
   - File attributes include metadata such as permissions, ownership, size, timestamps, and file type.
   - Directory attributes include permissions, ownership, size, timestamps, and the list of files and directories it contains.

2. **File Ownership**:
   - Every file and directory in UNIX has an owner and a group associated with it.
   - The owner is usually the user who created the file, while the group may be a specific user group.

3. **File Permissions**:
   - File permissions determine who can read, write, or execute a file or directory.
   - Permissions are represented by three sets of characters: owner, group, and others.
   - Each set consists of three characters: r (read), w (write), and x (execute).

4. **Changing File Permissions**:
   - Permissions can be changed using the `chmod` command.
   - Relative permission changes adjust permissions incrementally, while absolute permission changes set permissions explicitly.

5. **Changing File Ownership**:
   - The `chown` command is used to change the owner of a file or directory.
   - Syntax: `chown new_owner file_name`

6. **Changing Group Ownership**:
   - The `chgrp` command is used to change the group ownership of a file or directory.
   - Syntax: `chgrp new_group file_name`

7. **File System and Inodes**:
   - In UNIX, the file system is managed using inodes, which store metadata about files and directories.
   - Inodes contain information such as file type, permissions, ownership, timestamps, and pointers to data blocks.

8. **Hard Link vs. Soft Link**:
   - A hard link is a direct reference to an inode, allowing multiple filenames to point to the same data on disk.
   - A soft link, also known as a symbolic link, is a special type of file that points to another file by its path name.

9. **Significance of File Attribute for Directory**:
   - For directories, the permissions attribute controls access to the contents of the directory, including listing files and creating new files or directories inside it.

10. **Default Permissions of File and Directory and Using umask**:
    - Newly created files and directories inherit default permissions controlled by the umask value.
    - The umask value specifies which permissions are turned off by default when creating new files or directories.

11. **Listing of Modification and Access Time**:
    - The `ls` command with the `-l` option displays detailed information about files and directories, including modification and access times.

12. **Time Stamp Changing (touch)**:
    - The `touch` command is used to change file timestamps, including modification and access times.
    - Syntax: `touch file_name`

13. **File Locating (find)**:
    - The `find` command is used to locate files and directories based on various criteria, such as name, size, or permissions.
    - Syntax: `find starting_directory options criteria`