Certainly! Here's a cheatsheet in table format for LDAP enumeration using Nmap NSE scripts:

```
| NSE Script                                 | Description                                                     |
|--------------------------------------------|-----------------------------------------------------------------|
| `nmap -p 389 --script ldap-brute <target>`             | Performs brute force password guessing against LDAP.             |
| `nmap -p 389 --script ldap-rootdse <target>`           | Retrieves the root DSE (Directory System Entry) via LDAP.       |
| `nmap -p 389 --script ldap-search <target>`            | Performs a generic LDAP search on the target server.            |
| `nmap -p 389 --script ldap-novell-getpass <target>`    | Attempts to retrieve the user password using Novell eDirectory. |
| `nmap -p 389 --script ldap-vuln-cve2007-2447 <target>`  | Scans for the LDAP directory traversal vulnerability.           |
| `nmap -p 389 --script ldap-vuln-cve2015-1545 <target>`  | Scans for the LDAP directory administrator account lockout vulnerability. |
| `nmap -p 389 --script ldap-search <target>`                    | Performs a generic LDAP search on the target server.                           |
| `nmap -p 389 --script ldap-enum-users <target>`                | Enumerates user accounts via LDAP.                                             |
| `nmap -p 389 --script ldap-enum-groups <target>`               | Enumerates groups via LDAP.                                                    |
| `nmap -p 389 --script ldap-enum-privileges <target>`           | Enumerates privileges of LDAP user accounts.                                   |
| `nmap -p 389 --script ldap-enum-oid <target>`                   | Enumerates OIDs (Object Identifiers) via LDAP.                                 |
| `nmap -p 389 --script ldap-enum-schema <target>`                | Enumerates LDAP schema information.                                            |
| `nmap -p 389 --script ldap-enum-sessions <target>`              | Enumerates active sessions on the LDAP server.                                 |
| `nmap -p 389 --script ldap-enum-smb-ldap <target>`              | Enumerates SMB shares via LDAP.                                                |
| `nmap -p 389 --script ldap-enum-tasksched <target>`             | Enumerates scheduled tasks via LDAP.                                           |
| `nmap -p 389 --script ldap-enum-webservers <target>`            | Enumerates web servers via LDAP.                                               |
| `nmap -p 389 --script ldap-search <target> --script-args 'ldap.base="" ldap.search="(objectclass=*)" ldap.attributes=ALL'` | Performs a comprehensive LDAP search with all attributes. |
```

These NSE scripts can be executed with the `nmap` command, targeting port `389` (default LDAP port). Adjust the `<target>` parameter to the IP address or hostname of the LDAP server you wish to enumerate.
