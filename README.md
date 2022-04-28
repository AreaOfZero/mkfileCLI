# mkfileCLI
An easier way to create new files from the command line.

## Why did I make this?
I always have bad luck with adding file types to the "New" context menu in File Explorer, and the existing way of making new files in the command line sucks *(in my opinion, anyway)* and I thought "man, I wish this was just as easy as using the mkdir command" and so mkfile was born!

### An update to the purpose of this program
So.
After about 2 hours since I originally put this project onto GitHub, I was researching a better way to have the script work *(see Upcoming changes [link](#upcoming-changesto-do))*, and while I was looking at a guide on parameters, I found out about the "New-Item" command, which does exactly what I wanted in the first place, making this project pretty much worthless. However, I'll still keep this repository up and work on it as a way to continue learning how to write PowerShell scripts.

## How to use
1. Add path to mkfile.ps1 to your environment variables.
2. Open PowerShell.
3. Navigate to the directory you wish to create a new file in.
4. When prompted with "Input file to create", write the name of the file in the format of filename.extension *(i.e. newFile.md)*.
5. Ta-da! There should now be a new empty file created in the current directory!

## Upcoming changes/To-do
[ ] Once I learn more about writing PowerShell scripts, I will rewrite the script so that the name of the new file can be passed in as a parameter *(i.e. mkfile new.rs)*.