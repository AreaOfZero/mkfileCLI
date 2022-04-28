# mkfileCLI
An easier way to create new files from the command line.

## Why did I make this?
I always have bad luck with adding file types to the "New" context menu in File Explorer, and the existing way of making new files in the command line sucks *(in my opinion, anyway)* and I thought "man, I wish this was just as easy as using the mkdir command" and so mkfile was born!

## How to use
1. Add path to mkfile.ps1 to your environment variables.
2. Open PowerShell.
3. Navigate to the directory you wish to create a new file in.
4. When prompted with "Input file to create", write the name of the file in the format of filename.extension *(i.e. newFile.md)*.
5. Ta-da! There should now be a new empty file created in the current directory!

## Upcoming changes/To-do
Once I learn more about writing PowerShell scripts, I will rewrite the script so that the name of the new file can be passed in as a parameter *(i.e. mkfile new.rs)*.