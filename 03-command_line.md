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

>> show current working directory path: pwd
>> creating a directory: mkdir
>> deleting a directory: rm -r name_of_directory
>> creating a file using `touch` command: touch file.txt
>> deleting a file: rm -rf file.txt
>> renaming a file: mv file1.txt file2.txt
>> listing hidden files: ls -a
>> copying a file from one directory to another: cp source destination
>> accepts standard input and modifies it based on expression, before displaying it as output data: sed 's/word1/word2/' file.txt
>> displays the value of a single enviornment path: env | grep PATH
>> makes the variable to be available to all child sessions initiated from the session you are in. This is a way to make the variable persist across programs.: export USER='Cyrus Rustomji'

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

>> `ls`: lists files in current working directory
>> `ls -a`: lists all files in current working directory
>> `ls -l`: lists all files in a long format in the current working directory
>> `ls -lh`: lists all files in a long format and the current working directory in human readale format
>> `ls -lah`: lists all files in a long format, all files inclduing hidden files, and the current working directory in human readable format
>> `ls -t`: orders files and directories by the time they were modified
>> `ls -Glp`: Displays the long format listing, but exclude the owner name, the long format, and the directories with /

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

>> 'ls -b': Displays nonprinting characters in octal.
>> 'ls -o': Displays the long format listing, but excludes group name.
>> 'ls -r': Displays files in reverse order.
>> 'ls -u': Displays files by the file access time.
>> 'ls -1': Displays each entry on a line.

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

>> It is used to build and execute command from standard inoput. It converts input from standard input into arguments to a command.
>> touch file1.txt and echo file1.txt | xargs.txt are the same
>> xargs reads the STDIN data and converts each line into space seperated arguments to the command.
 

