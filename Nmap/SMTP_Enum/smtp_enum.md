Certainly! Here's a cheatsheet for Nmap SMTP enumeration using various scripts:

```
| NSE Script                                      | Description                                                             |
|-------------------------------------------------|-------------------------------------------------------------------------|
| `nmap -p 25 --script smtp-commands <target>`       | Send SMTP commands and retrieve server responses.                       |
| `nmap -p 25 --script smtp-enum-users <target>`     | Enumerate SMTP users.                                                   |
| `nmap -p 25 --script smtp-ntlm-info <target>`      | Retrieve NTLM authentication information from an SMTP server.           |
| `nmap -p 25 --script smtp-open-relay <target>`     | Check if the SMTP server allows open relay.                             |
| `nmap -p 25 --script smtp-strangeport <target>`    | Detect non-standard SMTP ports.                                         |
| `nmap -p 25 --script smtp-vuln-cve2010-4344 <target>` | Check if the SMTP server is vulnerable to CVE-2010-4344.              |
| `nmap -p 25 --script smtp-vuln-cve2011-1720 <target>` | Check if the SMTP server is vulnerable to CVE-2011-1720.              |
```

Adjust the parameters, such as `<target>`, according to your specific target SMTP server. These scripts can be used to send SMTP commands, enumerate users, retrieve authentication information, check for open relay, and detect vulnerabilities in SMTP servers.
