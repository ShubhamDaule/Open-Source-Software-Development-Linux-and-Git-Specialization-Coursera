## Bash Scripting

**Q1. Which of the following commands are equivalent (Select all answers that apply)?**

Answer:
* `if [[ -f file.c ]] ; then cat file.c ; fi`
* `if test -f file.c ; then cat file.c ; fi`
* `if [ -f file.c ] ; then cat file.c ; fi`
* `[[ -f file.c ]] && cat file.c`

**Q2. Which commands will list all files under the current directory ending in "~" (Select all answers that apply)?**
Note: Output lists may differ in format.

Answer:
* `find . -name "*~" -exec ls -l {} ';'`
* `find . -name "*~" -ls`
* `find . -name "*~" | xargs ls -l`
* `ls -l $(find . -name "*~")`

**Q3. Functions (subprograms) are useful in bash scripts because (Select all answers that apply):**

Answer:
* It is better not to have to call another script to get things done
* They make things easier to read and comprehend
* They eliminate the need to retype the same set of commands more than once

**Q4. How would you get the value of a variable named VAR into a script?**

Answer: 
* `read VAR`

**Q5. Select the correct statement:**

Answer: 
* A bash function must be placed before it is used in a script
