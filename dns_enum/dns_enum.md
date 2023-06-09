Certainly! Here's a cheatsheet for DNS enumeration commands:
```
| Command                                      | Description                                                             |
|----------------------------------------------|-------------------------------------------------------------------------|
| `nslookup <domain>`                           | Perform a DNS lookup for a specific domain.                              |
| `nslookup -type=<record_type> <domain>`       | Perform a DNS lookup for a specific record type of a domain.             |
| `dig <domain>`                                | Perform a DNS lookup for a specific domain using the dig command.        |
| `dig <record_type> <domain>`                  | Perform a DNS lookup for a specific record type of a domain using dig.   |
| `host <domain>`                               | Perform a DNS lookup for a specific domain using the host command.       |
| `host -t <record_type> <domain>`              | Perform a DNS lookup for a specific record type of a domain using host.  |
| `dnsrecon -d <domain>`                        | Perform DNS enumeration using the dnsrecon tool.                         |
| `enum4linux -A <target>`                      | Perform DNS enumeration and information gathering on Windows systems.   |
| `fierce -dns <domain>`                        | Perform DNS enumeration and zone transfer attempts using fierce tool.    |
| `dnsenum <domain>`                            | Perform DNS enumeration using the dnsenum tool.                          |
| `dnswalk <domain>`                            | Perform a zone transfer and display DNS information using dnswalk.       |
| `dmitry -s <domain>`                          | Perform DNS enumeration and gather information using dmitry tool.        |
| `recon-ng` (within the tool, use DNS modules) | Use the Recon-ng framework with DNS modules for enumeration.             |

```
