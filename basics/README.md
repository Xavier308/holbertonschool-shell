# Shell Basics

## Description
This repository contains scripts and exercises related to the basics of shell scripting. It covers topics such as navigating the file system, working with commands, manipulating files, and more.

## Resources
- [What Is “The Shell”?](#)
- [Navigation](#)
- [Looking Around](#)
- [A Guided Tour](#)
- [Manipulating Files](#)
- [Working With Commands](#)
- [Reading Man pages](#)
- [Keyboard shortcuts for Bash](#)
- [LTS](#)
- [Shebang](#)
- [Linux file systems summary](#)
- man pages: `cd`, `ls`, `pwd`, `less`, `file`, `ln`, `cp`, `mv`, `rm`, `mkdir`, `type`, `which`, `help`, `man`

## Learning Objectives

- General concepts such as what does RTFM mean, what is a Shebang, what is the Shell, the difference between a terminal and a shell, etc.
- Navigation commands and concepts like `cd`, `pwd`, `ls`, `.`, `..`, etc.
- Manipulating files using commands like `cp`, `mv`, `rm`, `mkdir`, etc.
- Working with commands such as `type`, `which`, `help`, `man`, etc.
- Understanding keyboard shortcuts for Bash and other related topics.

## Requirements
- Allowed editors: vi, vim, emacs
- Scripts tested on Ubuntu 20.04 LTS
- Scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All files should end with a new line

## Tasks
### Where am I?
Write a script that prints the absolute path name of the current working directory.

### What’s in there?
Display the contents list of your current directory.

### There is no place like home
Write a script that changes the working directory to the user’s home directory.

### The long format
Display current directory contents in a long format.

### Hidden files
Display current directory contents, including hidden files (starting with .). Use the long format.

### I love numbers
Display current directory contents in long format with user and group IDs displayed numerically, and include hidden files.

### Welcome
Create a script that creates a directory named my_first_directory in the /tmp/ directory.

### Betty in my first directory
Move the file betty from /tmp/ to /tmp/my_first_directory.

### Bye bye Betty
Delete the file betty from /tmp/my_first_directory.

### Bye bye My first directory
Delete the directory my_first_directory from /tmp.

### Back to the future
Write a script that changes the working directory to the previous one.

### Lists
Write a script that lists all files in the current directory, the parent directory, and the /boot directory in long format.

### File type
Write a script that prints the type of the file named iamafile in the /tmp directory.

### We are symbols, and inhabit symbols
Create a symbolic link to /bin/ls, named __ls__, in the current working directory.

### Copy HTML files
Create a script that copies all HTML files from the current working directory to the parent directory, but only if they don't already exist or are newer.

### Let’s move
Move all files beginning with an uppercase letter to the directory /tmp/u.

### Clean Emacs
Delete all files in the current directory that end with the character ~.

### Tree
Create directories welcome/, welcome/to/, and welcome/to/school in the current directory.

## Implemented by
Xavier J. Cruz (based on content by Julien Barbier)


