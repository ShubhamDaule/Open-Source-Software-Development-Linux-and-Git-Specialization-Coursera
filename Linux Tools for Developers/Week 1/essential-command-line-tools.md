## Essential Command Line Tools

**Q1. Which command will list all files under the current directory with a .cfg extension, and then delete them?**

Answer:
* `find . -name "*.cfg" -exec rm {} ';'`

**Q2. Which command will list all files and directories on the system with cfg in their name?**

Answer:
* `ls -l $(locate cfg)`

**Q3. Which command will find all files and directories in the system whose name ends with cfg?**

Answer:
* `locate -r "cfg$"`

**Q4. Which commands can change all occurrences within a file of the string boris to natasha (Select all answers that apply)?**

Answer:
* `sed -e s:boris:natasha:g file`
* `sed -e s/boris/natasha/g file`

**Q5. Which command will print out all lines beginning with "X" in all files in the current directory?**

Answer:
* `grep "^X" *`
