# PROCEDURE: 
 1.  Study the basic networking commands.
 2.  Run the networking commands along with their arguments and parameters. 
 3. Observe the output on the command line. 
 4. Record observations in the journal.2

# SOURCE CODE:
1. Tracert :
The tracert command prints the path. If all routers on the path are functional, this command prints the full path. If a router is down on the path, this command prints the path up to the last operational router.

tracert www.google.co.in

2. Ping :
The ping command is used to test connectivity between two hosts.

ping google.com

3. Arp :

By default, this command displays the ARP table of the active NIC. If multiple NICs are installed on the computer, you can use the -a option with this command. If the -a option is used, the ARP command displays all ARP tables.

arp -a 


4. netstat :

This command displays active connections, ports on which the computer is listening, Ethernet statistics, the IP routing table, and IP statistics.

Netstat

5. Ipconfig :
This command displays all current TCP/IP network configuration values and refreshes Dynamic Host Configuration Protocol (DHCP) and Domain Name System (DNS) settings. This command is mainly used to view the IP addresses on the computers that are configured to obtain their IP address automatically.

ipconfig
