## Networking

**Q1. Which networking configuration interface is newer and has extended capabilities?**

Answer:
* ip


**Q2. Using Predictable Network Interface Device Names (PNIDN) has come into use because:**

Answer:
* Many computers are no longer in one location; for example, laptops are on the move, and available interfaces are subject to change
*	Hardware such as USB devices can be added and removed at runtime
*	On modern systems, the order in which network hardware is found is less predictable


**Q3. Which command(s) will bring the network interface eth0 up and assign an address to it?**

Answer:
* sudo ip addr add 192.168.1.100 dev eth0
*	sudo ifconfig eth0 up 192.168.1.100


**Q4. You can see statistics for the eth0 interface by (select all answers that apply):**

Answer:
* looking at /sys/class/net/eth0/statistics
*	doing sudo ip -s link show eth0
*	doing sudo ifconfig eth0



**Q5. What does MTU stand for?**

Answer:
* Maximum Transfer Unit (usually 1500 bytes by default) for Ethernet packets

