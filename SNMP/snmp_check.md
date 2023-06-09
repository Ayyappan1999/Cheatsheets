Certainly! Here's a cheatsheet for the `snmp-check` command in table format:

```
| Command                                    | Description                                                          |
|------------------------------------------- |----------------------------------------------------------------------|
| `snmp-check -p <PORT> <TARGET>`            | Specify the SNMP port to use.                                        |
| `snmp-check -c <COMMUNITY> <TARGET>`       | Specify the SNMP community string to use for authentication.         |
| `snmp-check -v1 <TARGET>`                  | Use SNMPv1 protocol.                                                 |
| `snmp-check -v2c <TARGET>`                 | Use SNMPv2c protocol.                                                |
| `snmp-check -v3 <TARGET>`                  | Use SNMPv3 protocol.                                                 |
| `snmp-check -t <TIMEOUT> <TARGET>`         | Set the timeout value for SNMP requests.                             |
| `snmp-check -r <RETRIES> <TARGET>`         | Set the number of retries for failed SNMP requests.                  |
| `snmp-check -w <TARGET>`                   | Enable SNMP write requests (SNMPv2c or SNMPv3 required).             |
| `snmp-check -l <TARGET>`                   | Enable SNMP link layer discovery (SNMPv1 or SNMPv2c required).       |
| `snmp-check -m <MODULE> <TARGET>`          | Specify additional MIB modules to load.                              |
| `snmp-check -M <DIR> <TARGET>`             | Specify a directory to search for MIB files.                         |
```

These options can be used with the `snmp-check` command to perform SNMP enumeration and assessment. 
Replace `<PORT>`, `<COMMUNITY>`, `<TARGET>`, `<TIMEOUT>`, `<RETRIES>`, `<MODULE>`, and `<DIR>` with the appropriate values for your specific use case.
