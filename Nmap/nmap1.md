# NMAP 

Certainly! Here's a comprehensive cheatsheet for Nmap, a popular network scanning tool:

```
+-------------------------------------------------------------------------------------------------+
|                                     Nmap Commands Cheatsheet                                    |
+-----------------------------------+-------------------------------------------------------------+
|             Command               |                           Description                         |
+-----------------------------------+-------------------------------------------------------------+
| nmap <target>                     | Perform a basic scan on the target                           |
+-----------------------------------+-------------------------------------------------------------+
| nmap -p <port> <target>           | Scan a specific port on the target                           |
+-----------------------------------+-------------------------------------------------------------+
| nmap -p- <target>                 | Scan all ports on the target                                 |
+-----------------------------------+-------------------------------------------------------------+
| nmap -F <target>                  | Scan the most common ports on the target                     |
+-----------------------------------+-------------------------------------------------------------+
| nmap -sS <target>                 | Perform a TCP SYN scan                                       |
+-----------------------------------+-------------------------------------------------------------+
| nmap -sT <target>                 | Perform a TCP connect scan                                   |
+-----------------------------------+-------------------------------------------------------------+
| nmap -sU <target>                 | Perform a UDP scan                                           |
+-----------------------------------+-------------------------------------------------------------+
| nmap -sV <target>                 | Perform version detection                                    |
+-----------------------------------+-------------------------------------------------------------+
| nmap -O <target>                  | Perform operating system detection                           |
+-----------------------------------+-------------------------------------------------------------+
| nmap -A <target>                  | Perform aggressive scan (OS detection, version detection, etc.) |
+-----------------------------------+-------------------------------------------------------------+
| nmap -p- -sV -sC <target>         | Scan all ports with version detection and default scripts    |
+-----------------------------------+-------------------------------------------------------------+
| nmap --top-ports <number> <target>| Scan the top <number> ports on the target                    |
+-----------------------------------+-------------------------------------------------------------+
| nmap -iL <file>                   | Read targets from a file                                     |
+-----------------------------------+-------------------------------------------------------------+
| nmap -oN <file> <target>          | Save scan results in normal format to a file                 |
+-----------------------------------+-------------------------------------------------------------+
| nmap -oX <file> <target>          | Save scan results in XML format to a file                    |
+-----------------------------------+-------------------------------------------------------------+
| nmap -oG <file> <target>          | Save scan results in grepable format to a file               |
+-----------------------------------+-------------------------------------------------------------+
| nmap --script <script> <target>   | Run a specific NSE script against the target                 |
+-----------------------------------+-------------------------------------------------------------+
| nmap --script <category> <target> | Run scripts from a specific category against the target       |
+-----------------------------------+-------------------------------------------------------------+
| nmap --script-help <script>       | Display help for a specific NSE script                       |
+-----------------------------------+-------------------------------------------------------------+
| nmap --script-updatedb            | Update NSE script database                                   |
+-----------------------------------+-------------------------------------------------------------+
| nmap -T<0-5> <target>             | Set the scan timing template                                 |
+-----------------------------------+-------------------------------------------------------------+
| nmap -v <target>                  | Increase verbosity level of the output                       |
+-----------------------------------+-------------------------------------------------------------+
| nmap -h                           | Display Nmap help and usage information                      |
+-----------------------------------+-------------------------------------------------------------+
```

These are some commonly used commands and options in Nmap.
