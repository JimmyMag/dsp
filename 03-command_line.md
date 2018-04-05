# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

pwd - show current working directory path
mkdir - create a directory
rmdir - remove empty directory
touch *file* - creates *file*
rm - removes file
mv *old* *new* - renames a file
ls -a - all files in directory
cp *target* *destination* - copies files
cd *directory* - navigate to specified directory
man *command* - opens the manual for the specified command

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

ls - list directory contents
ls -a - do not ignore entries starting with .
ls -l - use a long listing format
ls -lh - print sizes in human readable format
ls -lah - print sizes in human readable format, including entries starting with .
ls -t - sort by modification time
ls -Glp - long listing without printing group names, appending / indicator to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

ls -r - reverse order when sorting
ls -R - list subdirectories recursively
ls -s - sort by file size
ls -U - do not sort
ls -B - do not list implied entries ending with ~

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

Build and execute command lines from standard input.  For example, the command line arguments could be imported and run from a file instead of being typed into the command line individually.

 

