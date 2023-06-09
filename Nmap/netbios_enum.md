Certainly! Here's a cheatsheet in table format for NetBIOS enumeration using Nmap NSE scripts:

```
| NSE Script                     | Description                                                           |
|--------------------------------|-----------------------------------------------------------------------|
| `nmap -p 139,445 --script=smb-vuln* <target>`      | Scans for common SMB vulnerabilities.                                   |
| `nmap -p 137,138 --script=nbstat.nse <target>`     | Retrieves NetBIOS statistics and information.                           |
| `nmap -p 137,138 --script=nbstat.nse --script-args='nbstat.timeout=1s' <target>` | Adjusts the timeout for the nbstat script.              |
| `nmap -p 139,445 --script=smb-enum* <target>`       | Performs various SMB enumeration tasks, such as user, share, and group enumeration. |
| `nmap -p 139,445 --script=smb-os-discovery <target>`| Attempts to determine the operating system running on the target system.  |
| `nmap -p 137,138 --script=nbtscan.nse <target>`     | Discovers NetBIOS name information on a target network.                  |
| `nmap -p 139,445 --script=smb-security-mode <target>` | Determines the security mode of the SMB server.                       |
| `nmap -p 139,445 --script=smb-enum-domains <target>` | Enumerates Windows domains via SMB.                                     |
| `nmap -p 139,445 --script=smb-enum-groups <target>`  | Enumerates Windows domain groups via SMB.                               |
| `nmap -p 139,445 --script=smb-enum-processes <target>` | Enumerates running processes on a Windows system via SMB.             |
```

These NSE scripts can be executed with the `nmap` command, targeting the appropriate ports (`139` for NetBIOS Session Service and `445` for SMB). 
Adjust the `<target>` parameter to the IP address or hostname of the target system you wish to enumerate.

