# 0x00. Shell, basics

## Task 1

* 0. Where am I?  

## Objective

Write a script that prints the absolute path name of the current working directory.

## Task 2

* 1. What’s in there?

## objective

Display the contents list of your current directory.

## Task 3

* 2. There is no place like home

## objective 

Write a script that changes the working directory to the user’s home directory.

## Task 4

* 3. The long format

## objective

 Display current directory contents in a long format

## Task 5

* 4. Hidden files

## objective 

Display current directory contents, including hidden files (starting with .). Use the long format.

## Task 6

* 5. I love numbers

## objective 

Display current directory contents.

## Task 7

* 6. Welcome 

## objective

Create a script that creates a directory named myfirstdirectory in the /tmp/ directory.

## Task 8

* 7. Betty in my first directory

## objective 

Move the file betty from /tmp/ to /tmp/myfirstdirectory.

## Task 9

* 8. Bye bye Betty

## objective

Delete the file betty.

## Task 10

* 9. Bye bye My first directory

## objective

Delete the directory myfirstdirectory that is in the /tmp directory.

## Task 11

* 10. Back to the future

## objective 

Write a script that changes the working directory to the previous one.

## Task 12 

* 11. Lists

## objective

Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

## Task 13

* 12. File type

## objective

Write a script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

## Task 14

* 13. We are symbols, and inhabit symbols

## objective 

Create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.

## Task 15 

* 14. Copy HTML files

## objective

Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

You can consider that all HTML files have the extension .html



## Requirements

* Allowed editors: vi, vim, emacs
* All your scripts will be tested on Ubuntu 20.04 LTS
* All your scripts should be exactly two lines long ($ wc -l file should print 2)
* All your files should end with a new line (why?)
* The first line of all your files should be exactly #!/bin/bash
* A README.md file at the root of the repo, containing a description of the repository
* A README.md file, at the root of the folder of this project, describing what each script is doing
* You are not allowed to use backticks, &&, || or ;
* All your scripts must be executable. To make your file executable, use the chmod command: chmod u+x file. Later, we’ll learn more about how to utilize this command.
