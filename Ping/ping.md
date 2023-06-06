# PING COMMANDS

Certainly! Here's a cheatsheet for the `ping` command-line utility, which is commonly used to test network connectivity and measure round-trip time (RTT) between a source and a destination:

```
+-------------------------------------------------------+
|               Ping Command Utility                    |
+-------------------------+-----------------------------+
|        Command          |         Description         |
+-------------------------+-----------------------------+
| ping <host>             | Send ICMP echo request to   |
|                         | the specified host          |
+-------------------------+-----------------------------+
| ping -c <count> <host>  | Send a specified number     |
|                         | of ICMP echo requests to    |
|                         | the specified host          |
+-------------------------+-----------------------------+
| ping -t <ttl> <host>    | Set the time-to-live (TTL)  |
|                         | value for the ICMP packets  |
+-------------------------+-----------------------------+
| ping -s <size> <host>   | Set the size of ICMP echo   |
|                         | request packets (bytes)     |
+-------------------------+-----------------------------+
| ping -i <interval> <host>| Set the interval between    |
|                         | sending ICMP echo requests  |
+-------------------------+-----------------------------+
| ping -w <timeout> <host>| Set the timeout (in seconds) |
|                         | for waiting for a response  |
+-------------------------+-----------------------------+
| ping -l <preload> <host>| Set the number of ICMP echo  |
|                         | request packets to send     |
|                         | before waiting for a        |
|                         | response                    |
+-------------------------+-----------------------------+
| ping -a <host>          | Resolve IP addresses to     |
|                         | hostnames (reverse DNS)     |
+-------------------------+-----------------------------+
| ping -4 <host>          | Force using IPv4 for ping   |
+-------------------------+-----------------------------+
| ping -6 <host>          | Force using IPv6 for ping   |
+-------------------------+-----------------------------+
| ping -n <host>          | Bypass DNS resolution and   |
|                         | use IP address directly     |
+-------------------------+-----------------------------+
| ping -v <host>          | Verbose output, display     |
|                         | detailed information        |
+-------------------------+-----------------------------+
| ping -h                 | Display help menu           |
+-------------------------+-----------------------------+
```
