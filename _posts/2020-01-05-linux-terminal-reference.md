---
title: Linux Terminal Quick Reference
date: 2020-01-05 00:00:00 Z
categories:
- reference
layout: post
excerpt: A quick reference of commonly used Linux shortcuts and commands that I find
  useful. This reference will be updated as more shortcuts and commands are added
  or removed.
comments: false
share: true
---

A quick reference of commonly used Linux shortcuts and commands that I find useful. 
This reference will be updated as more shortcuts and commands are added or removed. 

Last updated: 01-03-2020

{% include toc %}

## Shortcut Keys 
A collection of useful shortcut keys for bash which is the default shell in most Linux system.

### Alt Key Shortcuts 
Alt key shortcuts are mostly used to manipulate the command text that is inputted into the shell terminal 

Key Combination | Affects 
:---: | :---: 
Alt + A | Go to beginning of line 
Alt + B | Move cursor back one character 
Alt + F | Move cursor forward one character 
Alt + U | Capitalize the word after the cursor 
Alt + L | Lowercase the word after the cursor 
Alt + T | Swap the last two words
Alt + R | Undo changes made to command retrieved using Ctrl + R (bash history search) 
Alt + . | Use the last word or parameter from the previous command in the new command 
Alt + C | Suspend the running command or process, similar to Ctrl + C 
Alt + D | If the terminal is empty, closes the terminal. If there is text, delete all characters after the cursor 

### Ctrl Key Shortcuts 
Ctrl key shortcuts are used to manipulate command text as well as interact with the shell terminal. 

Key Combination | Affects 
:---: | :---: 
Ctrl + A | Go to beginning of line 
Ctrl + E | Go to end of the line 
Ctrl + B | Move cursor back one character 
Ctrl + F | Move cursor forward one character 
Ctrl + H | Delete the character before the cursor 
Ctrl + D | Delete the character under the cursor
Ctrl + U | Delete all characters before the cursor
Ctrl + W | Delete a word before the cursor
Ctrl + Y | Paste the last item deleted or cut
Ctrl + T | Swap the last two character
Ctrl + S | Search bash history
Ctrl + R | Reverse search bash history
Ctrl + G | Leave history searching mode
Ctrl + L | Clear the screen
Ctrl + C | Stop the currently running command
Ctrl + Z | Pause the currently running command and backgrounds it.
Ctrl + D | Delete the character under the cursor 

### Bash Bang Shortcuts 
Bash Bang (_!_) shortcuts are used to manipulate the command that was just entered. 

Key Combination | Affects 
:---: | :---: 
!! | Run last command
!blah | Run last command that starts with '_blah_'
!blah:p | Print the command of _!blah_ without running it
!$ | Use the last word or parameter from the previous command in the new command
!$:p | Print the value of _!$_

## Filesystem Commands 
Getting around the Linux filesystem and interacting with it. 

Command | Description 
:---: | :---: 
ls | List files in current working directory
touch | Create a file
cp | Copy a file
mv | Move a file
rm | Delete a file
cd | Change to a directory. If ran by itself, returns to home folder
mkdir | Create a directory
rmdir | Deletes an _empty_ directory
chmod | Change the mode of the file or directory
chown | Change the owner the file or directory
chgrp | Change the group membership of the file or directory
cat | Print out the contents of a file
head | Prints the top few lines of a file
tail | Prints the last few lines of a file
less | Prints out the content of a file interactively
wc | Counts the words on screen

## Archive Files Commands 
Manipulating archived or compressed files.

### Compressing and Archiving Files 

Command | Description 
:---: | :---: 
tar -cvf ./file.tar \<dir_to_compress\> | Create a tar file 
tar -cvzf ./newfile.tar.gz \<dir_to_compress\> | Create a tar.gz file 
tar -cvzf ./newfile.tgz \<dir_to_compress\> | Create a tgz file 
zip -r ./file.zip \<dir_to_compress\> | Create a zip file 

### Decompressing and Unarchiving Files.

Command | Description 
:---: | :---: 
tar -xvf ./file.tar | Extract a tar file 
tar -xvzf ./newfile.tar.gz | Extract a tar.gz file 
tar -xvzf ./newfile.tgz | Extract a tgz file 
unzip ./file.zip | Extract a zip file 
