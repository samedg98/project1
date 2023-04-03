# Project 1

# Samed Ganibegovic

# Linux System Calls and Library Functions

Brief Description:
The goal of this project is to become familiar with the environment in hoare while practising system calls

bt [-h] [-L -d -g -i -p -s -t -u | -l] [dirname]

The options are to be interpreted as follows:
h - Print a help message and exit.
L - Follow symbolic links, if any. Default will be to not follow symbolic links.
t - Print information on file type.
p - Print permission bits asrwxrwxrwx.
i - Print the number of links to file in inode table.
u - Print theUIDassociated with the file.
g - Print theGIDassociated with the file.
s - Print the size of file in bytes.  If the size is larger than 1K, indicate the size in KB with a suffix K; if the size is larger than1M, indicate the size in MB with a suffix M; if the size is larger than 1G, indicate the size in GB with a suffix G.
d - Show the time of last modification.
l - This option will be used to print information on the file as if the optionstpiugsare all specified.

If the user does not specifydirname, run the command using current directory and print the tree accordingly

How to compile and run the assignment:

In order to run the project, you would need to type "make" into the command prompt.
A .o file will be generated as well as an executable file.
You would then need to type: ./bt [dirname] in order to use it.
You should be able to see the list of directories and files in the current working directory, or selected path directory.
More options can be displayed through ./bt -h.

Any issues with the program, and/or problems encountered:

I had a lot of trouble with this project, mainly with the breadth first search traversal and the queue.
I couldn't grasp the concept completely, and I ended up confusing it a bit with depth first search.
I looked through resources online for help and got something running.
I was able to get the options down.


********

EDIT: 

Was able to get some code to compile.

********



link to version control:

https://github.com/samedg98/project1
