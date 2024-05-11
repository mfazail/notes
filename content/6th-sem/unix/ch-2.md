# CH 2
1. **File System**:
   - The file system in UNIX is a hierarchical structure that organizes and stores files and directories.
   - It provides a way to access and manage data stored on disk drives or other storage devices.

2. **Types of Files**:
   - In UNIX, there are three main types of files: regular files, directories, and special files.
   - Regular files contain data, directories organize files and other directories, and special files represent hardware devices or system resources.

3. **File Naming Convention**:
   - File names in UNIX can contain letters, numbers, and certain special characters like hyphens (-) and underscores (_).
   - File names are case-sensitive, meaning "File.txt" and "file.txt" are considered different files.

4. **Parent-Child Relationship**:
   - In the UNIX file system, directories can contain files and other directories.
   - Each directory has a parent directory, except for the root directory (/), which is the top-level directory in the file system hierarchy.

5. **HOME Variable**:
   - The HOME environment variable points to the home directory of the current user.
   - It is typically set to /home/username, where "username" is the name of the user.

6. **Inode Number**:
   - In UNIX, each file and directory is associated with an inode, which stores metadata about the file or directory.
   - The inode number uniquely identifies each file or directory within the file system.

7. **Absolute Pathname vs. Relative Pathname**:
   - An absolute pathname specifies the full path of a file or directory from the root directory (/).
   - A relative pathname specifies the path of a file or directory relative to the current directory.

8. **Significance of Dot (.) and Dotdot (..)**:
   - The dot (.) represents the current directory.
   - The dotdot (..) represents the parent directory.

9. **Displaying Pathname of the Current Directory (pwd)**:
   - The pwd command displays the absolute pathname of the current working directory.

10. **Changing the Current Directory (cd)**:
    - The cd command is used to change the current working directory.
    - For example, "cd /usr/bin" changes the current directory to /usr/bin.

11. **Make Directory (mkdir)**:
    - The mkdir command is used to create a new directory.
    - For example, "mkdir mydir" creates a directory named "mydir".

12. **Remove Directories (rmdir)**:
    - The rmdir command is used to remove empty directories.
    - For example, "rmdir mydir" removes the directory named "mydir".

13. **Listing Contents of Directory (ls)**:
    - The ls command is used to list the contents of a directory.
    - For example, "ls -l" lists the contents of the current directory in long format.

14. **Important File Systems of UNIX**:
    - /bin: Contains essential system binaries and commands.
    - /usr/bin: Contains user binaries and commands.
    - /sbin: Contains system binaries used for system administration tasks.
    - /usr/sbin: Contains system administration binaries for non-essential system tasks.
    - /etc: Contains system configuration files.
    - /dev: Contains device files representing hardware devices.
    - /lib: Contains shared libraries needed for system boot and operation.
    - /usr/lib: Contains additional shared libraries.
    - /usr/include: Contains header files used for software development.
    - /usr/share/man: Contains manual pages for various commands and utilities.
    - /tmp: Provides a temporary directory for storing files.
    - /var: Contains variable data files, such as logs and spool directories.
    - /home: Contains user home directories.