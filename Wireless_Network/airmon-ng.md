Certainly! Here's a cheatsheet for BetterCAP:

| Command                                           | Description                                               |
|---------------------------------------------------|-----------------------------------------------------------|
| `bettercap`                                       | Start BetterCAP.                                          |
| `set <option> <value>`                            | Set a specific option to a value.                         |
| `show <option>`                                   | Show the current value of a specific option.              |
| `help`                                            | Display the help menu.                                    |
| `help <command>`                                  | Display help for a specific command.                      |
| `show interfaces`                                 | Show available network interfaces.                        |
| `set interface <interface>`                       | Set the network interface to use.                         |
| `show targets`                                    | Show currently targeted hosts.                            |
| `target <host>`                                   | Target a specific host.                                   |
| `mitm on`                                         | Enable Man-in-the-Middle (MITM) attacks.                  |
| `mitm off`                                        | Disable Man-in-the-Middle (MITM) attacks.                 |
| `show modules`                                    | Show available modules.                                   |
| `use <module>`                                    | Select a module for use.                                  |
| `show options`                                    | Show available options for the selected module.           |
| `set <option> <value>`                            | Set a specific option to a value for the selected module. |
| `run`                                             | Run the selected module.                                  |
| `set arp.spoof.targets <target>`                   | Set the target for ARP spoofing.                          |
| `set dns.spoof.hosts <target> <redirect>`          | Set the target for DNS spoofing and redirect URL.         |
| `set sslstrip.http_only true`                     | Enable HTTP-only SSL stripping.                           |
| `set sslstrip.hsts_bypass true`                   | Enable HSTS bypass for SSL stripping.                     |
| `set sslstrip.strip_all true`                     | Strip SSL from all connections.                           |
| `set dns.spoof.enabled true`                      | Enable DNS spoofing.                                      |
| `set dns.spoof.domains <domains>`                  | Set the domains to spoof for DNS spoofing.                |
| `set dns.spoof.ip <ip>`                           | Set the IP address to redirect for DNS spoofing.          |
| `set dns.spoof.ttl <ttl>`                         | Set the TTL (Time to Live) value for DNS responses.       |
| `net.probe on`                                    | Enable network probing.                                   |
| `net.probe off`                                   | Disable network probing.                                  |
| `http.proxy on`                                   | Enable HTTP proxy.                                        |
| `http.proxy off`                                  | Disable HTTP proxy.                                       |
| `http.proxy.sslstrip on`                          | Enable SSL stripping for HTTP proxy.                      |
| `http.proxy.sslstrip off`                         | Disable SSL stripping for HTTP proxy.                     |
| `http.proxy.sslstrip.bypass_certs <certs_list>`    | Bypass SSL certificates for specific domains.             |
| `net.recon on`                                    | Enable network reconnaissance.                            |
| `net.recon off`                                   | Disable network reconnaissance.                           |
| `exit`                                            | Exit BetterCAP.                                           |
