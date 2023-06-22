## Shells, Bash, and the Command Line


**Q1. Which of the following commands would add newbin, a directory in your home directory, to the PATH (Select all answers that apply)?**

Answer:
* PATH=$PATH:$HOME/newbin
* PATH=$HOME/newbin:$PATH

**Q2. To make an environment variable (VAR) effective for only one command (foobar), you should do:**

Answer: 
* VAR=value ./foobar

**Q3. Which of the following expressions will give the correct mathematical result (7) for x = 10 (Select all answers that apply)?**

Answer:
* $ echo $(($x - 3 ))
*	$ echo $(expr $x - 3)

**Q4. Which commands will get both the normal and error outputs of prog into afile?**

Answer:
* foo > file 2>&1 
* foo >& file

**Q5. Which of the following commands has the correct syntax for specifying an alias?**

Answer:	
* alias doitall="make clean; make all; evince output.pdf" 
