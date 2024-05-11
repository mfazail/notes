# CH 3

1. **Displaying and Creating Files (cat)**:
   - The `cat` command is used to display the contents of a file on the terminal.
   - It can also be used to concatenate multiple files and display their contents.
   - To create a new file, you can use redirection or a text editor like `vi` or `nano`.

2. **Copying a File (cp)**:
   - The `cp` command is used to copy files or directories.
   - Syntax: `cp source_file destination_file`

3. **Deleting a File (rm)**:
   - The `rm` command is used to delete files or directories.
   - Syntax: `rm file_name`

4. **Renaming/Moving a File (mv)**:
   - The `mv` command is used to rename or move files or directories.
   - Syntax: `mv old_file_name new_file_name`

5. **Paging Output (more)**:
   - The `more` command is used to display the contents of a file one page at a time.
   - It allows scrolling through the file using the spacebar or arrow keys.

6. **Printing a File (lp)**:
   - The `lp` command is used to print files on a printer.
   - Syntax: `lp file_name`

7. **Knowing File Type (file)**:
   - The `file` command is used to determine the type of a file.
   - Syntax: `file file_name`

8. **Line, Word, and Character Counting (wc)**:
   - The `wc` command is used to count lines, words, and characters in a file.
   - Syntax: `wc file_name`

9. **Comparing Files (diff)**:
   - The `diff` command is used to compare the contents of two files and display the differences.
   - Syntax: `diff file1 file2`

10. **Finding Common Between Two Files (comm)**:
    - The `comm` command is used to compare two sorted files line by line and display lines that are common or unique to each file.
    - Syntax: `comm file1 file2`

11. **Displaying File Differences (diff)**:
    - The `diff` command is used to display the differences between two files.
    - Syntax: `diff file1 file2`

12. **Creating Archive File (tar)**:
    - The `tar` command is used to create and manipulate archive files.
    - Syntax to create: `tar -cvf archive_name.tar file1 file2 directory`

13. **Compressing File (gzip)**:
    - The `gzip` command is used to compress files.
    - Syntax: `gzip file_name`

14. **Uncompressing File (gunzip)**:
    - The `gunzip` command is used to uncompress gzip-compressed files.
    - Syntax: `gunzip file_name.gz`

15. **Archive File (zip)**:
    - The `zip` command is used to create compressed archive files.
    - Syntax: `zip archive_name.zip file1 file2 directory`

16. **Extracting Compressed File (unzip)**:
    - The `unzip` command is used to extract files from a zip archive.
    - Syntax: `unzip archive_name.zip`

17. **Effect of cp, rm, and mv Command on Directory**:
    - When the `cp` command is used with a directory as the destination, it copies the source file or directory into the destination directory.
    - When the `rm` command is used with a directory, it deletes the directory and all its contents recursively.
    - When the `mv` command is used to move a file into a directory, it moves the file into the directory. If the destination is a file, it renames the file.