## Users and Groups

**Q1. Basic information about the characteristics of a user's account can be found in:**

Answer: The basic information about a user's account can be found in the `/etc/passwd` file.

**Q2. Adding a new user to a group is done with:**

Answer: To add a new user to a group, you can use the `usermod` command.

**Q3. Which provides stronger security and auditing for system activity:**

Answer: `sudo` provides stronger security and auditing for system activity.

**Q4. Differences between su and su - include (Select all answers that apply):**

Answer:
* `su` preserves more information, such as the current directory, path, and environment variables.
* `su -` starts a new login shell, while `su` just continues the current shell but gives it super privileges.

**Q5. Which is the proper way to use sudo with echo?**

Answer: The proper way to use sudo with echo is `sudo bash -c "echo 3 > /proc/sys/vm/drop_caches"`.




