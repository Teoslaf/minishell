# MiniShell
MiniShell is a project designed to introduce students to the fundamentals of Unix shell programming and system calls in the C programming language. Much like Cub3D, MiniShell is part of the curriculum at 42, an innovative coding school focused on peer-to-peer learning and project-based education.

## Project Overview:
MiniShell is inspired by Unix shells like Bash or Zsh. The goal of this project is to create a simplified version of a Unix shell, capable of executing basic commands and managing processes.

## Features:
Command Execution: Implement the ability to execute commands entered by the user.
Built-in Commands: Support built-in commands such as cd, echo, pwd, etc.
Environment Variables: Manage environment variables, including setting, displaying, and unsetting them.
Redirection: Support input and output redirection (<, >), as well as piping (|) between commands.
Signal Handling: Handle signals such as Ctrl+C (SIGINT) and Ctrl+Z (SIGTSTP).
Command History: Allow users to access and navigate command history using arrow keys.
Tab Completion: Implement tab completion for commands and file paths.
Scripting: Support executing shell scripts.

## Installation:
To compile and run the MiniShell project, follow these steps:
Clone the project repository.
Navigate to the project directory.
Run the make command to compile the project.
Execute the generated executable.

## Usage:
```bash
./minishell
```
## Controls:
Arrow Keys: Navigate command history.
Tab: Autocomplete commands and file paths.
Ctrl+C: Interrupt currently running command.
Ctrl+D: Suspend currently running command.

## Dependencies:
C compiler (gcc or clang)
Standard C libraries
Knowledge of Unix system calls

# Example:

```bash
$ ./minishell
$ ls
file1.txt file2.txt directory
$ cd directory
$ pwd
/home/user/directory
$ echo "Hello, world!"
Hello, world!
$ exit
```

