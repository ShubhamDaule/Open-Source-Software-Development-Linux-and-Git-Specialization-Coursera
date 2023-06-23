
## Kernel Modules and Device Management

**Q1. Which statements are true?**

Answer:
* It is impossible to unload a kernel module being used by an application.
* It is impossible to unload a kernel module being used by another module.

**Q2. The lsmod utility shows for each loaded module (select all correct answers):**

Answer:
* How many processes depend on it.
* Its size in bytes.
* What other modules are using it.

**Q3. Udev (select all correct answers):**

Answer:
* Loads and unloads device drivers and other kernel modules as needed.
* Stands for User Device.
* Is responsible for populating the /dev directory once the system is up and running.

**Q4. Which command will ensure the httpd service (Apache) starts at system boot?**

Answer: `sudo systemctl enable httpd.service`

**Q5. How could you ensure the httpd service (Apache) is restarted if it is already running, say to absorb a revised configuration file (select all correct answers)?**

Answer:
* `sudo systemctl stop httpd && sudo systemctl start httpd`
* `sudo systemctl restart httpd
