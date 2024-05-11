# CH 6

1. **Use of Environment Variables**:
   - Environment variables are dynamic values that affect the behavior of processes running in the operating system.
   - Common environment variables include:
     - **HOME**: Specifies the user's home directory.
     - **PATH**: Specifies the directories to search for executable files.
     - **LOGNAME**: Specifies the login name of the user.
     - **USER**: Specifies the username of the user.
     - **TERM**: Specifies the terminal type.
     - **PWD**: Specifies the present working directory.
     - **PS1**: Specifies the primary prompt string.
     - **PS2**: Specifies the secondary prompt string.

2. **Aliases**:
   - Aliases are user-defined shortcuts for commands or command sequences.
   - They are created using the `alias` command.
   - Example: `alias ll='ls -l'` creates an alias ll for the ls -l command.

3. **Brief Idea of Command History**:
   - Command history allows users to view and reuse previously executed commands.
   - The history command displays a list of previous commands.
   - Users can recall and execute previous commands using the !n syntax, where n is the command number.

4. **Filters**:
   - Filters are commands that process input data and produce modified output.
   - Common filters include:
     - **pr**: Prepares files for printing by adding headers, footers, and page breaks.
     - **head** and **tail**: Display the first or last few lines of a file.
     - **cut**: Cuts out selected portions of each line of a file.
     - **paste**: Merges lines of files horizontally.
     - **sort**: Sorts lines of text files.
     - **uniq**: Filters adjacent matching lines from a sorted file.
     - **tr**: Translates or deletes characters from standard input and writes to standard output.
     - **grep**: Searches files for lines that match a pattern.

5. **Searching Pattern using grep**:
   - The `grep` command is used to search for patterns in files.
   - Basic Regular Expression (BRE) and Extended Regular Expression (ERE) are used to specify search patterns.
   - **Basic Regular Expression (BRE)**: Uses basic metacharacters like ., *, [], ^, and $ for pattern matching.
   - **Extended Regular Expression (ERE)**: Extends BRE with additional metacharacters like +, ?, (), and |.

6. **grep -f**:
   - The `grep -f` command is used to search for multiple patterns stored in a file.