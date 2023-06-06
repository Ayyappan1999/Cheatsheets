# DNSRecon 

Certainly! Here's a cheatsheet for the `dnsrecon` tool, a powerful DNS enumeration and reconnaissance tool:

```
+-------------------------------------------------------+
|                     dnsrecon Tool                      |
+-------------------------+-----------------------------+
|        Command          |         Description         |
+-------------------------+-----------------------------+
| dnsrecon -d <domain>    | Perform a standard DNS      |
|                         | reconnaissance on the       |
|                         | specified domain            |
+-------------------------+-----------------------------+
| dnsrecon -t <target>    | Perform a standard DNS      |
|                         | reconnaissance on the       |
|                         | specified target (IP)       |
+-------------------------+-----------------------------+
| dnsrecon -D <file>      | Perform DNS reconnaissance  |
|                         | on a list of domains        |
|                         | from a file                 |
+-------------------------+-----------------------------+
| dnsrecon -z <zone>      | Enumerate all domains       |
|                         | within a specified DNS zone |
+-------------------------+-----------------------------+
| dnsrecon -a <address>   | Reverse DNS lookup on a     |
|                         | specified IP address        |
+-------------------------+-----------------------------+
| dnsrecon -r <range>     | Perform reverse DNS lookup  |
|                         | on a specified IP range     |
+-------------------------+-----------------------------+
| dnsrecon -e <engine>    | Specify a specific search   |
|                         | engine for data collection  |
+-------------------------+-----------------------------+
| dnsrecon -i <interval>  | Set the interval (in        |
|                         | seconds) between requests   |
+-------------------------+-----------------------------+
| dnsrecon -t <threads>   | Set the number of threads   |
|                         | to use for concurrent       |
|                         | requests                    |
+-------------------------+-----------------------------+
| dnsrecon -c             | Display additional DNS      |
|                         | record information          |
+-------------------------+-----------------------------+
| dnsrecon -b             | Perform bruteforcing        |
|                         | using a wordlist             |
+-------------------------+-----------------------------+
| dnsrecon -w <wordlist>  | Use a custom wordlist for   |
|                         | bruteforcing                |
+-------------------------+-----------------------------+
| dnsrecon -f             | Enable fast mode, skips     |
|                         | querying multiple DNS       |
|                         | servers                     |
+-------------------------+-----------------------------+
| dnsrecon -s             | Enable stealth mode,        |
|                         | reduces noise in output     |
+-------------------------+-----------------------------+
| dnsrecon -v             | Verbose output, display     |
|                         | detailed information        |
+-------------------------+-----------------------------+
| dnsrecon -h             | Display help menu           |
+-------------------------+-----------------------------+
```

These are the commonly used commands and options for the `dnsrecon` tool. Use them to perform comprehensive DNS enumeration, information gathering, and brute-forcing operations on domains, IP addresses, and DNS zones.
