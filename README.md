# shell-data-processing

## Command line commands

## For Directories
- To make a new directory
	``` $ mkdir <directory> ```
- To change directory
  ``` $ cd <directory> ```
- To display the current working directory
  ``` $ pwd ```
  
## Output
- The cat command allows us to create single or multiple files, view contain of file, concatenate files and redirect output in terminal or files.
  ``` $ cat <file> ```
- To output the first 10 lines of the file
  ``` $ head <file> ```
- To direct the output of cmd into file
  ``` $ <cmd> > <file> ```
- To append the ouput of cmd to file 
  ``` $ <cmd> >> <file> ```
- To clear the command line window
  ``` $ clear ```

## Search
- "grep" command is used to search text. It searches the given file for lines containing match to the given strings or words

 - Search any line that contains the word in the filename 
   ``` $ grep 'word' filename ```
 - Search for all files containing word inside directory
   ``` $ grep -rl "word" <directory> ```

## Shortcuts
- ``` CTRL+A ```  moves the caret to the begining.
- ``` CTRL+E ```  moves caret to the end of the line.
- ``` CTRL+K ```  Delete all character after the caret.
- ``` CTRL+U ```  Deletes all charaters infront of caret.

## Bash shell Commands

- ls - list directory contents
  - ``` $ ls -a ``` list all files including hidden starting with '.'
  - ``` $ ls -d ``` list directories
  - ``` $ ls -l ``` list with long format
  - ``` $ ls -ls ``` list with long format with readable file size
- echo - Prints to the terminal window
  - ``` $ echo -n ``` newline is omitted from the output.
  - ``` $ echo -e ``` This enables the function of backslash.
  - ``` $ echo -E ``` This disable the function of backslash.
- touch - Creates a new file.
 - ``` $ touch -a ``` This is used to change access time.
 - ``` $ touch -c ``` This command is used to check whether file is created or not.
- ``` $ rmdir ``` - Removes  empty directories.
- ``` $ locate ``` - Simple way to find the file or directory.
- ``` $ less ``` - This command allows you to view files without opening an editor.

## 

## References
[Command_Line_reference](https://www.git-tower.com/blog/command-line-cheat-sheet/)
[Bash_Reference](https://www.educative.io/blog/bash-shell-command-cheat-sheet)
 
