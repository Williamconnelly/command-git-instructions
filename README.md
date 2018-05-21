#Navigation Terminal
**cd** -> Change directory
- cd ~ -> change directory to Home
**ls** -> Display what is in current directory with short list
**l** -> Display complete file information in directory
**pwd** -> Print working directory
**open** -> Command will open a file in default program or directory in finder

#File Manipulation
**man** -> Pulls up manual for commands - q to exit
- `man [command here]` -- will display information about the command
**|** -> Pipe will execute command on left first then execute command on right
- `[command here] | [second command]` -- does not work for every command
**>** -> Redirects output to a file
- `echo "text to add" > [File name]` - Output directed into file !!! Will overwrite
- `echo "text to add" >> [File name]` - Output appended into file
**mkdir** -> Create new directory from current position
**touch** -> Create new file within current directory
**mv** -> Move files
- `mv [current file name] [new file name]` -- will rename the file
- `mv [current file name] ./newdirectory/[new file name]` -- will move the file and rename, directory must exist. "." in directory indicates current directory
**rm** -> Removes files or directories
- `rm [file name]` -- removes files from system
- `rm -r [directory name]` -- Removes directory and all subsequent files
**grep** -> Will search through documents for strings
- `cat [file name] | grep "string to search"` -- Will search contents of file and return if grep string is found
- `-n` -- Will display line number of found string
- `-A [num]` -- Will display trailing number of lines specified
- `-B [num]` -- Will display preceding number of lines specified
**cat** -> Reads a fils(s) and outputs to Terminal
- `cat [file name]` -- Will display file contents
- `cat [file name] [file name] ....` -- will display file contents of all files selected in order