# 10 Useful Shell Commands

## What are "Shell Commands"?

> A.k.a "Command-Line Commands" or "Terminal Commands"

- text-based instructions entered into a command-line interface or shell to perform specific tasks or operations on a computer systems

### My Ten Most Useful Shell Commands

1. % **cd**

    - *change directory*
    - navigate and switch between different directories or folders in a CLI
    `% cd folder`
    `% cd folder2/folder1`
    `% cd "My Folder"`
    `% cd .` - *current directory*
    `% cd ..` - *move one level up in directory*
    `% cd /` *or* `% cd` - *move to root directory*

2. % **ls**

    - *list*
    - list the files and directories in the current directory
    `% ls`
    `% ls -l` - more details
    `% ls -a` - all files including hidden

3. % **pwd**

    - *print working directory*
    - display the current working directory; prints the dull path of the directory you are currently in
    `% pwd`

4. % **mkdir**

    - *make directory*
    - create a new directory in the current working directory
    `% mkdir folder`
    `% mkdir folder1 folder2 folder3`

5. % **touch**

    - create a new, empty files
    - update the access and modification times of existing files
    `% touch file.md`
    `% touch file1.md file2.md file3.md`
    `% touch folder1/file1.md`

6. % **rm**

    - *remove*
    - remove or delete files and directories in a CLI
    `% rm file.md`
    `% rm file1.md file2.md file3.md`
    `% rm -r folder1` - -r or -R enables recursive deletion for directories

7. % **mv**

    *move*
    - move files and directories
    - rename files and directories
    `% mv file.md NewFolder/` - move file to new location
    `% mv file.md file2.md` - rename file w/o moving to a new location

8. % **alias**

    - create custom shortcuts or aliases for other commands
    - allows you to define a shorter or more convenient name for a longer or frequently used command or command-sequence
    `% alias` - see a list of currently defined aliases
    `% alias details="ls -l"` - "AliasName="CommandName"
    `% unalias details` - remove/override an existing alias

9. % **echo**

    - print or display text or variables to the terminal
    - display a message:
        - `% echo "Hello, world!"
            - `Hello, world!`
    - display the values of variables
        - `name="Kayla"`
        - `% echo $name`
            - Kayla

10. % **history**

    - display a list of previously executed commands
    - can limit the number of commands displayed
    `% history -n 10`
    - can search command history for specific commmands or patterns using the `|` (pipe) operator and the `grep` command
    `% history | grep git`
