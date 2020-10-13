# Bash Commands Cheatsheet

Here's a cheatsheet I'm using to remember some of the most common `bash` commands:

## Navigating the file system

### The 'cd' command:  
This is a command that stands for `change directory` and is commonly used to navigate the file system
* `cd ~` takes you back home
* `cd filename` takes you to the desired location that you choose

### List a directory's contents  
This is the command for listing out everything in the directory(folder) `ls`. if you want to see everything, including the hidden, use this command `ls -a`. 

If you have `tree` downloaded, type in `tree` to get a nice diagram of the contents within your directory. 

### Create a directory 
Use the command `mkdir` to create new directories. 
* example: `mkdir new-file-name`

### Creating files
Use the `touch` command. 

### Moving Files
Us the `mv` command. Heres how to move one file to another directory:
`mv ~/directory1/folder/file ~/directory1/otherfolder`

### Renaming files 
This is like moving the file but using the same directory but with a different name: 
* `mv ~/drawers/pjs/warm.pjs ~/drawers/pjs/summer.pjs`

### Deleting Files
Use the `rm` command to delete both files
* ex: `rm filename`

### Deleting Directories
Use the command `rm -r` to delete a directory and it's files. If the directory is empty, just use `rm`.

### Copying Files and Directores
Use the `cp` command for files and the `cp -R` command for entire directories 

### Clearing the history 
You can type the command `clear` or press `cmd k`. You are still able to see history by using the up arrow or by scrolling up.  