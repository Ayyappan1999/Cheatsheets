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

```
| Command                                      | Description                                                             |
|----------------------------------------------|-------------------------------------------------------------------------|
| `dnsrecon -d <domain>`                        | Perform a basic DNS reconnaissance on the specified domain.              |
| `dnsrecon -t rvl -d <domain>`                  | Perform a reverse lookup on the specified domain.                        |
| `dnsrecon -t axfr -d <domain>`                 | Attempt an AXFR zone transfer on the specified domain.                   |
| `dnsrecon -t brt -d <domain>`                  | Perform a brute force enumeration of DNS subdomains.                     |
| `dnsrecon -t srv -d <domain>`                  | Enumerate DNS SRV records for the specified domain.                       |
| `dnsrecon -t std -d <domain>`                  | Perform a standard DNS enumeration on the specified domain.              |
| `dnsrecon -t zonewalk -d <domain>`             | Perform a DNS zone walk on the specified domain (if zone transfer allowed). |
| `dnsrecon -t rvl -D <ip_list_file>`            | Perform reverse DNS lookups on a list of IP addresses from a file.        |
| `dnsrecon -t rvl -f <ip_range>`                | Perform reverse DNS lookups on an IP address range.                       |
| `dnsrecon -t axfr -n <nameserver> -d <domain>` | Attempt an AXFR zone transfer using a specific nameserver.                |
```

These are the commonly used commands and options for the `dnsrecon` tool. Use them to perform comprehensive DNS enumeration, information gathering, and brute-forcing operations on domains, IP addresses, and DNS zones.

