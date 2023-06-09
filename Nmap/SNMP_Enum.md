Certainly! Here's a cheatsheet in table format for SNMP enumeration using Nmap NSE scripts:
```
| NSE Script                          | Description                                                           |
|-------------------------------------|-----------------------------------------------------------------------|
| `nmap -p 161 --script=snmp-brute <target>`             | Performs brute force password guessing against SNMP.                   |
| `nmap -p 161 --script=snmp-hh3c-logins <target>`       | Attempts to log in to SNMP-enabled devices using default credentials.  |
| `nmap -p 161 --script=snmp-info <target>`              | Retrieves system information via SNMP.                                 |
| `nmap -p 161 --script=snmp-netstat <target>`           | Retrieves active TCP connections and listening UDP ports via SNMP.     |
| `nmap -p 161 --script=snmp-processes <target>`         | Retrieves running processes on a remote system via SNMP.               |
| `nmap -p 161 --script=snmp-sysdescr <target>`          | Retrieves the system description via SNMP.                             |
| `nmap -p 161 --script=snmp-win32-services <target>`    | Retrieves a list of installed Windows services via SNMP.               |
| `nmap -p 161 --script=snmp-win32-shares <target>`      | Retrieves a list of shared resources on a Windows system via SNMP.     |
| `nmap -p 161 --script=snmp-win32-software <target>`    | Retrieves a list of installed software on a Windows system via SNMP.   |
| `nmap -p 161 --script=snmp-win32-users <target>`       | Retrieves a list of local user accounts on a Windows system via SNMP.  |
```
These NSE scripts can be executed with the `nmap` command, targeting port `161` (default SNMP port). Adjust the `<target>` parameter to the IP address or hostname of the target system you wish to enumerate.
