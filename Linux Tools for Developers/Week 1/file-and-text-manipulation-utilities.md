## File and Text Manipulation Utilities

**Q1. Which command is used to combine three files into a fourth file?**

Answer:
* `cat file1 file2 file3 > file4`

**Q2. Which of the following commands can be used to view the last 15 lines of a file (Select all answers that apply)?**

Answer:
* `tail -15 some_file`
* `tail -n15 some_file`

**Q3. Which of the following commands will replace all instances of the word "dog" with "pig" in the file named some_file and send the output to stdout (Select all answers that apply)?**

Answer:
* `sed -e s:dog:pig:g some_file`
* `sed -e s/dog/pig/g some_file`
* `cat some_file | sed -e s/dog/pig/g`

**Q4. Which commands can be used to print the lines that contain the numbers 0–5 in a file (Select all answers that apply)?**

Answer:
* `grep [0,1,2,3,4,5] filename`
* `grep [0-5] filename`

**Q5. Which command is used to extract columns from a file to work on them later?**

Answer:
* `cut`
