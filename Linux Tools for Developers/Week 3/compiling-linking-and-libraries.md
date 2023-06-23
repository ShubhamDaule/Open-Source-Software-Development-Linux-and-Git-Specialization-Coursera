## Compiling, Linking and Libraries

**Q1. GCC stands for:**

Answer: 
* GNU Compiler Collection

**Q2. A good choice of compiler options for day-to-day use would be:**

Answer: 
* `gcc -O2 -Wall -pedantic program.c`

**Q3. Why might you choose to link your program statically, rather than use a shared library version?**

Answer: 
* The static program will not use new versions of shared libraries as they become available, and thus may avoid breakage and bugs

**Q4. To find the shared libraries used by /usr/bin/cp you can do (Select all answers that apply):**

Answer:
* `ldd $(which cp)`
* `ldd /usr/bin/cp`

**Q5. Which statements are true (Select all answers that apply):**

Answer:
* Use of shared libraries can cause bugs because the application may conflict with the new library version
* Applications can load faster when using shared libraries
* Use of shared libraries saves memory
* Use of shared libraries enables applications to stay up to date with new library features without being recompiled
