The following table is a list of shortcuts I use for reference.
Maybe you can make use of this curated list as well.

To generate the table in markdown I copy from the working table and paste it into this markdown converter tool:
https://thisdavej.com/copy-table-in-excel-and-paste-as-a-markdown-table/

## Shortcuts

| Shortcut                             | App              | Description                                                                                                                                       |
|:--------------------------------------|:------------------|:---------------------------------------------------------------------------------------------------------------------------------------------------|
| cmd+shift+c                          | Maccy            | Shows clipboard history                                                                                                                           |
| Ctrl + A                             | Terminal         | Go to the beginning of the line you are currently typing on. This also works for most text input fields system wide. Netbeans being one exception |
| Ctrl + E                             | Terminal         | Go to the end of the line you are currently typing on. This also works for most text input fields system wide. Netbeans being one exception       |
| Ctrl + L                             | Terminal         | Clears the Screen                                                                                                                                 |
| Cmd + K                              | Terminal         | Clears the Screen                                                                                                                                 |
| Ctrl + U                             | Terminal         | Cut everything backwards to beginning of line                                                                                                     |
| Ctrl + K                             | Terminal         | Cut everything forward to end of line                                                                                                             |
| Ctrl + W                             | Terminal         | Cut one word backwards using white space as delimiter                                                                                             |
| Ctrl + Y                             | Terminal         | Paste whatever was cut by the last cut command                                                                                                    |
| Ctrl + H                             | Terminal         | Same as backspace                                                                                                                                 |
| Ctrl + C                             | Terminal         | Kill whatever you are running. Also clears everything on current line                                                                             |
| Ctrl + D                             | Terminal         | Exit the current shell when no process is running, or send EOF to a the running process                                                           |
| Ctrl + Z                             | Terminal         | Puts whatever you are running into a suspended background process. fg restores it                                                                 |
| Ctrl + _                             | Terminal         | Undo the last command. (Underscore. So it's actually Ctrl + Shift + minus)                                                                        |
| Ctrl + T                             | Terminal         | Swap the last two characters before the cursor                                                                                                    |
| Ctrl + F                             | Terminal         | Move cursor one character forward                                                                                                                 |
| Ctrl + B                             | Terminal         | Move cursor one character backward                                                                                                                |
| Option + →                           | Terminal         | Move cursor one word forward                                                                                                                      |
| Option + ←                           | Terminal         | Move cursor one word backward                                                                                                                     |
| Esc + T                              | Terminal         | Swap the last two words before the cursor                                                                                                         |
| Esc + Backspace                      | Terminal         | Cut one word backwards using none alphabetic characters as delimiters                                                                             |
| Tab                                  | Terminal         | Auto-complete files and folder names                                                                                                              |
| cd [folder]                          | Terminal         | Change directory e.g. cd Documents                                                                                                                |
| cd                                   | Terminal         | Home directory                                                                                                                                    |
| cd ~                                 | Terminal         | Home directory                                                                                                                                    |
| cd /                                 | Terminal         | Root of drive                                                                                                                                     |
| cd -                                 | Terminal         | Previous directory                                                                                                                                |
| ls                                   | Terminal         | Short listing                                                                                                                                     |
| ls -l                                | Terminal         | Long listing                                                                                                                                      |
| ls -a                                | Terminal         | Listing incl. hidden files                                                                                                                        |
| ls -lh                               | Terminal         | Long listing with Human readable file sizes                                                                                                       |
| ls -R                                | Terminal         | Entire content of folder recursively                                                                                                              |
| sudo [command]                       | Terminal         | Run command with the security privileges of the superuser (Super User DO)                                                                         |
| open [file]                          | Terminal         | Opens a file ( as if you double clicked it )                                                                                                      |
| top                                  | Terminal         | Displays active processes. Press q to quit                                                                                                        |
| nano [file]                          | Terminal         | Opens the file using the nano editor                                                                                                              |
| vim [file]                           | Terminal         | Opens the file using the vim editor                                                                                                               |
| clear                                | Terminal         | Clears the screen                                                                                                                                 |
| reset                                | Terminal         | Resets the terminal display                                                                                                                       |
| [command-a]; [command-b]             | Terminal         | Run command A and then B, regardless of success of A                                                                                              |
| [command-a] && [command-b]           | Terminal         | Run command B if A succeeded                                                                                                                      |
| [command-a] || [command-b]           | Terminal         | Run command B if A failed                                                                                                                         |
| [command-a] &                        | Terminal         | Run command A in background                                                                                                                       |
| [command-a] | [command-b]            | Terminal         | Run command A and then pass the result to command B e.g ps auxwww | grep google                                                                   |
| history n                            | Terminal         | Shows the stuff typed – add a number to limit the last n items                                                                                    |
| Ctrl + r                             | Terminal         | Interactively search through previously typed commands                                                                                            |
| ![value]                             | Terminal         | Execute the last command typed that starts with ‘value’                                                                                           |
| ![value]:p                           | Terminal         | Print to the console the last command typed that starts with ‘value’                                                                              |
| !!                                   | Terminal         | Execute the last command typed                                                                                                                    |
| !!:p                                 | Terminal         | Print to the console the last command typed                                                                                                       |
| touch [file]                         | Terminal         | Create a new file                                                                                                                                 |
| pwd                                  | Terminal         | Full path to working directory                                                                                                                    |
| .                                    | Terminal         | Current folder, e.g. ls .                                                                                                                         |
| ..                                   | Terminal         | Parent/enclosing directory, e.g. ls ..                                                                                                            |
| ls -l ..                             | Terminal         | Long listing of parent directory                                                                                                                  |
| cd ../../                            | Terminal         | Move 2 levels up                                                                                                                                  |
| cat                                  | Terminal         | Concatenate to screen                                                                                                                             |
| rm [file]                            | Terminal         | Remove a file, e.g. rm data.tmp                                                                                                                   |
| rm -i [file]                         | Terminal         | Remove with confirmation                                                                                                                          |
| rm -r [dir]                          | Terminal         | Remove a directory and contents                                                                                                                   |
| rm -f [file]                         | Terminal         | Force removal without confirmation                                                                                                                |
| cp [file] [newfile]                  | Terminal         | Copy file to file                                                                                                                                 |
| cp [file] [dir]                      | Terminal         | Copy file to directory                                                                                                                            |
| mv [file] [new filename]             | Terminal         | Move/Rename, e.g. mv file1.ad /tmp                                                                                                                |
| pbcopy < [file]                      | Terminal         | Copies file contents to clipboard                                                                                                                 |
| pbpaste                              | Terminal         | Paste clipboard contents                                                                                                                          |
| pbpaste > [file]                     | Terminal         | Paste clipboard contents into file, pbpaste > paste-test.txt                                                                                      |
| mkdir [dir]                          | Terminal         | Create new directory                                                                                                                              |
| mkdir -p [dir]/[dir]                 | Terminal         | Create nested directories                                                                                                                         |
| rmdir [dir]                          | Terminal         | Remove directory ( only operates on empty directories )                                                                                           |
| rm -R [dir]                          | Terminal         | Remove directory and contents                                                                                                                     |
| less [file]                          | Terminal         | Output file content delivered in screensize chunks                                                                                                |
| [command] > [file]                   | Terminal         | Push output to file, keep in mind it will get overwritten                                                                                         |
| [command] >> [file]                  | Terminal         | Append output to existing file                                                                                                                    |
| [command] < [file]                   | Terminal         | Tell command to read content from a file                                                                                                          |
| find [dir] -name [search_pattern]    | Terminal         | Search for files, e.g. find /Users -name "file.txt"                                                                                               |
| grep [search_pattern] [file]         | Terminal         | Search for all lines that contain the pattern, e.g. grep "Tom" file.txt                                                                           |
| grep -r [search_pattern] [dir]       | Terminal         | Recursively search in all files in specified directory for all lines that contain the pattern                                                     |
| grep -v [search_pattern] [file]      | Terminal         | Search for all lines that do NOT contain the pattern                                                                                              |
| grep -i [search_pattern] [file]      | Terminal         | Search for all lines that contain the case-insensitive pattern                                                                                    |
| mdfind [search_pattern]              | Terminal         | Spotlight search for files (names, content, other metadata), e.g. mdfind skateboard                                                               |
| mdfind -onlyin [dir] -name [pattern] | Terminal         | Spotlight search for files named like pattern in the given directory                                                                              |
| [command] -h                         | Terminal         | Offers help                                                                                                                                       |
| [command] --help                     | Terminal         | Offers help                                                                                                                                       |
| info [command]                       | Terminal         | Offers help                                                                                                                                       |
| man [command]                        | Terminal         | Show the help manual for [command]                                                                                                                |
| whatis [command]                     | Terminal         | Gives a one-line description of [command]                                                                                                         |
| apropos [search-pattern]             | Terminal         | Searches for command with keywords in description                                                                                                 |
| cmd-p or cmd-t                       | Atom Text Editor | Opens the Fuzzy Finder palette in which you can search and open files                                                                             |
| cmd-b                                | Atom Text Editor | Browse tabs within the window                                                                                                                     |
| alt-cmd-left                         | Atom Text Editor | Cycles left through open tabs (in the active pane)                                                                                                |
| alt-cmd-right                        | Atom Text Editor | Cycles right through open tabs (in the active page)                                                                                               |
| cmd-\                                | Atom Text Editor | Toggles Atom's file Tree View                                                                                                                     |
| shift-cmd-d                          | Atom Text Editor | Duplicates the line of the current cursor position and creates a new line under it with the same contents                                         |
| ctrl-shift-k                         | Atom Text Editor | Deletes the current line                                                                                                                          |
| ctrl-m                               | Atom Text Editor | The cursor goes to the matching top bracket that the cursor is ecapsulated in                                                                     |
| cmd-l                                | Atom Text Editor | Selects the entire line the cursor's current position is in                                                                                       |
| cmd-/                                | Atom Text Editor | Toggles the selected text into a comment of the current grammar                                                                                   |
| cmd-d                                | Atom Text Editor | Select Same Words                                                                                                                                 |
| cmd-ctrl-g                           | Atom Text Editor | Select All The Same Words At Once                                                                                                                 |
| ctrl-alt-b                           | Atom Text Editor | Beautify package                                                                                                                                  |
