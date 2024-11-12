A Hive Helsinki project, init, which introduces system and network commands, services used on a server machine and scripts that can be useful for SysAdmins on a daily basis.
The following questions are answered in the files located inside the network, system and scripts folders.

Network
1. Get the list of the network interfaces of the machine without displaying any detail
for these interfaces. Only the list of names.
2. Identify and display the Ethernet interface characteristics:
(a) Identify broadcast address
(b) Identify all IP adresses which are part of the same subnet
3. Identify the MAC address of the Wi-Fi card
4. Identifiy the default gateway in the routing table
5. Identify the IP address of the DNS that responds to the following url: who.int
6. Get the complete path of the file that contains the IP address of the DNS server
you’re using
7. Query an external DNS server on the who.int domain name (ie.: google 8.8.8.8)
8. Find the provider of who.int
9. Find the external IP of 42.fr
10. Identify the network devices between your computer and the who.int domain
11. Use the output of the previous command to find the name and IP address of the
device that makes the link between you (local network) and the outside world
12. Find the IP that was assigned to you by dhcp server
13. Thanks to the previous question and the reverse DNS find the name of your host
14. What file contains the local DNS entries?
15. Make the intra.42.fr address reroute to 46.19.122.85

System
1. In what file can you find the installed version of your Debian?
2. What command can you use to rename your system?
3. What file has to be modified to make it permanent?
4. What command gives you the time since your system was last booted?
5. Name the command that determines the state of the SSH service.
6. Name the command that reboots the SSH service.
7. Figure out the PID of the SSHD service.
8. What file contains the RSA keys of systems that are authorized to connect via SSH?
9. What command lets you know who is connected to the System?
10. Name the command that lists the partition tables of drives?
11. Name the command that displays the available space left and used on the system
in an humanly understandable way
12. Figure out the exact size of each folder of /var in a humanly understandable way
followed by the path of it.
13. Name the command that find, in real time, currently running processes
14. Run the ‘tail -f /var/log/syslog‘ command in background
15. Find the command that kills the background command’s process
16. Find the service which makes it possible to run specific tasks following a regular
schedule
17. Find the command that allows you to connect via ssh on the VM. (In parallel with
the graphic session)
18. Find the command that kills ssh service
19. List all services which are started at boot time and name this kind of services
20. List all existing users on the VM
21. List all real users on the VM
22. Find the command that add a new local user
23. Explain how connect yourself as new user. (With graphic session and ssh session)
24. Find the command that list all packages

Scripting
1. Write a script which displays only the login, UID and Path of each entry of the
/etc/passwd file.
2. Write a script which deletes an ACTIVE user on the VM.
3. Three’s a Charm. Write a script of you choice.


