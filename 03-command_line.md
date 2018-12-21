# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.

> > 
* man                         :man pages provide access to reference manuals
* pwd                         :current working directory path
* mkdir                       :creating a directory
* rm -r dir_name              :deleting a directory
* touch file_name             :creating a file using `touch` command
* rm file_name                :deleting a file
* mv file_name new_file_name  :renaming a file
* ls -a                       :listing hidden files
* cp file_name /file/dir/.    :copying a file from one directory to another
* cd ..                       :change to parent dir
* grep -i some_word *         :search in working dir (case insensitive)
* echo 'Hello World'          :display line of text 
* print first 3 lines of file :head -3 file_name
* cat file_name               :concatenate and display content of file

---

### Q2.  List Files in Unix   

What do the following commands do:  
> > 
* `ls`      :list directory contents (for non-hidden files)
* `ls -a`   :(-a == all) lists all files including hidden files (which start with .)
* `ls -l`   :(-l == long list format) returns an alphabetical list of non-hidden files with added information (access rights, who last updated it, file size, and timestamp of last update)
* `ls -lh`  :(-h == human-readable), displays easy to read file size format (ie, 10K or 100G)
* `ls -lah` :combines -l, -a, and -h arguments which will list and describe all files in human readable format
* `ls -t`   :(-t == time) sort by time, newest first
* `ls -Glp` :(-G == no-group) don't include group names in long list and append / to directories

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > 
* ls -rtl (long list given by oldest first)
* ls -R   (list subdirs recursively)
* ls -Sl  (long list, sort by size with largest first)
* ls -X   (sort alphabetically by ext)
* ls -1   (list a single file per line)

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > 
* xargs: build and execute command lines from standard input
* Example: xargs find -name '*.txt' ctrl+d this will search for the name of the file (input through stdin) using find command
