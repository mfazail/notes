# CH 5

1. **Shell**:
   - The shell is a command-line interpreter that allows users to interact with the operating system.
   - It interprets user commands and executes them by interacting with the kernel.
   - The interpretive cycle of the shell involves reading, parsing, and executing commands entered by the user.

2. **Types of Shell**:
   - Common shells in UNIX include:
     - **Bourne Shell (sh)**: The original UNIX shell.
     - **Bash (Bourne Again Shell)**: A widely used shell, compatible with sh and incorporating additional features.
     - **C Shell (csh)**: Shell with C-like syntax.
     - **Korn Shell (ksh)**: Enhanced version of the Bourne Shell with additional features.

3. **Pattern Matching**:
   - Pattern matching, also known as wildcard expansion, allows users to specify sets of files using wildcard characters like * and ?.

4. **Escaping and Quoting**:
   - Escaping (\) allows users to treat special characters literally.
   - Quoting ('', "") prevents interpretation of special characters by the shell.

5. **Redirection**:
   - Redirection allows users to control where input comes from and where output goes.
   - Examples include redirecting standard output (>), standard input (<), and standard error (2>).

6. **Standard Input, Standard Output, Standard Error**:
   - Standard input (stdin), standard output (stdout), and standard error (stderr) are streams through which data flows between programs and the shell.
   - By default, stdin is the keyboard, stdout is the terminal, and stderr is the terminal for error messages.

7. **/dev/null and /dev/tty**:
   - /dev/null is a special device file that discards all data written to it and returns EOF when read.
   - /dev/tty refers to the controlling terminal device.

8. **Pipe and tee**:
   - Pipe (|) allows the output of one command to be used as input for another command.
   - tee command copies input to both stdout and one or more files.

9. **Command Substitution**:
   - Command substitution allows the output of a command to replace the command itself.
   - Syntax: $(command) or \`command\`

10. **Shell Variables**:
    - Shell variables hold data or values used by the shell and user programs.
    - Examples include environment variables like PATH and user-defined variables.

11. **Process**:
    - A process is an instance of a running program in the operating system.
    - It consists of program code, data, stack, heap, and process control block (PCB).

12. **Display Process Attributes (ps)**:
    - The `ps` command displays information about active processes.
    - Syntax: `ps aux` or `ps -ef`

13. **Display System Processes**:
    - System processes are processes managed by the operating system kernel.
    - They include processes such as init, getty, and kernel threads.

14. **Process Creation Cycle**:
    - The process creation cycle involves the fork, exec, and wait system calls.
    - Fork creates a new process, exec loads and executes a new program, and wait waits for the child process to terminate.

15. **Shell Creation Steps**:
    - Shell creation involves several steps, including initialization (init), login, and launching the user's shell.

16. **Process State**:
    - Processes can be in various states, including running, sleeping, stopped, and zombie.

17. **Background Jobs, Foreground Jobs**:
    - Background jobs are processes that run independently of the shell, allowing the user to continue working in the foreground.
    - The `&` operator is used to run a command in the background.

18. **Using Signals to Kill Process**:
    - Signals are software interrupts used to communicate with processes.
    - The `kill` command sends signals to processes, allowing users to terminate or control them.

19. **Job Control Commands**:
    - Job control commands like `bg`, `fg`, `jobs`, `kill`, and `ctrl+z` are used to manage background and foreground jobs.

20. **Executing at Specified Time (at and batch)**:
    - The `at` and `batch` commands are used to execute commands or scripts at a specified time or when system load is low.