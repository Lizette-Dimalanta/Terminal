# **Terminal/Command Line**

### Tuesday, 9 August 2022.
 
# Definitions
### Command-Line/Command Prompt:
- Type of interface (device/program enabling user to communicate with computer).

### Terminal Prompt:
`lizette@LIZETTE-MACHETE:~$`
- Wrapper Program: Programs/Code that 'wrap' around other program components.
- Runs a shell and allows user to enter commands.

### Console:
- Type of terminal
- A window in which your text-mode programs are active.

### REPL:
- Read-Execute-Print-Loop

# Cheat Sheet 
- ### `~` : Tilde
    1. `~` : Current directory location
    2. `cd ~` : Takes you to home.

- ### `clear`:
    1. `Clear`
    2. `[Ctrl] + L`
    
            Clears terminal.

- ### `history`:
        Shows command history.

- ### `pwd`: Print Working Directory
        Shows current directory location.

- ### `cd [directory]`: Change Directory
        Changes into stated directory.

- ### `mkdir`: Make New Directory
        Creates new directory (folder).

- ### `ls [directory]`: List
        Lists files/folders in selected directory.

- ### `'.'` : Relative Directories
        . = Current Directory
        .. = Parent Directory (1 line up)
        ../.. = Moves Up 2 Parent Directories

- ### `touch[name.txt]`: Create File
        Creates new file.

- ### `more[name.txt]`: File Information
        Views contents of file.

- ### `mv`: Move/Rename
    1. `mv[file/folder][new-name]`: Rename (within directory)
    2. `mv[file/folder][new-directory-location]`: Renames & Moves file/folder into specified directory.
            
            Moves/Renames directory (if stated).

- ### `cp`: Copy
    1. Copy File:  `cp[file-origin.txt][file-copy.txt]`
    2. Copy File in Specified Directory: `cp[file.txt][directory location]`

            Copies file/folder into stated directory location.

- ### `-a`: Flag/Option
        '-rf' f = force

- ### `rm [file.txt]`: Remove File
        Deletes file.
        *(hard deletion)

- ### `rm -rf [directory]`: Remove Directory
        Deletes directory and its contents.
        *(hard deletion)

- ### `man [command]`: Command Information
        Provides information about specified command.
        'q': Quits Manual

- ### `echo [text]`: Embed Text
        `echo = FALSE`: Prevents code, but not results from appearing in finished file.

- ### `'>'`: Redirect (File)
        Takes output of command -> puts it into file.
        *Will not work with directories

- ### `cat`: View File Content
        View contents in a file.

- ### `help`: Command List
        Shows Command List.

- ### `sudo[command]`: Super User Do
        Executes command under root user.

- ### `code .`: Run Code Editor (VSC)
        Opens file in VSC.

